
pipeline {
  agent { label 'docker' }
  stages {
    stage('Build') {
      agent {
        docker {
          label 'docker'
          alwaysPull true
          image 'deneir/node-build:latest'
          registryUrl 'https://419456231856.dkr.ecr.us-gov-west-1.amazonaws.com'
          args "-u root:root"
        }       
      }
      steps {
        sh '''
        git clean -fxd
        npm i
        npm run build
        '''
      }
    }
  }
}