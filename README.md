# TACHYONS

Functional CSS for humans. Our fork of `tachyons-css/tachyons` wwhich implements an AstroUXDS inspired style guide. 

Quickly build and design new UI without writing CSS.

## Principles

* Everything should be 100% responsive
* Everything should be readable on any device
* Everything should be as fast as possible
* Designing in the browser should be easy
* It should be easy to change any interface or part of an interface without breaking any existing interfaces
* Doing one thing extremely well promotes reusability and reduces repetition
* Documentation helps promote reusability and shared knowledge
* CSS shouldn't impede accessibility or the default functionality of HTML
* You should send the smallest possible amount of code to the user

## Features

* Mobile-first CSS architecture
* 490 accessible color combinations
* 8px baseline grid
* Multiple debugging utilities to reduce layout struggles
* Single-purpose class structure
* Optimized for maximum gzip compression
* Lightweight (~14kB)
* Usable across projects
* Growing open source component library
* Works well with plain HTML, React, Ember, Angular, Rails and more
* Infinitely nestable responsive grid system
* Built with PostCSS

## Getting Started

Docs can be found at http://tachyons.io/docs
The modules are generally pretty small and thus quick and easy to read.

### Local Setup

Clone the repo from Github and install dependencies through npm.

```
git clone https://github.com/OutsideAnalytics/deneir_tachyons.git
cd deneir_tachyons
npm install
```

#### Dev

If you want to just use everything in tachyons/src as a jumping off point and
edit all the code yourself, you can compile all of your wonderful changes by
running:

```npm start```

This will output both minified and unminified versions of the CSS to the CSS directory and watch the src directory for changes.
It's aliased to the command:

```npm run build:watch```

If you'd like to just build the CSS once without watching the src directory, run:

```npm run build```

If you want to check that a class hasn't been redefined or 'mutated,' there is a linter to check that all of the classes have only been defined once. This can be useful if you are using another library or have written some of your own CSS and want to make sure there are no naming collisions. To do this run the command:

```npm run mutations```

## Docs

The tachyons docs located at http://tachyons.io are all open source and located at https://github.com/tachyons-css/tachyons-css.github.io

You can clone the docs and use them as a template for documenting your own design system / patterns / components.
While not everything is automated, the component library generation makes it extremely easy to
generate and organize the documentation for components as demonstrated at http://tachyons.io/components

### Community Resources

- [DWYL Learn Tachyons](https://github.com/dwyl/learn-tachyons): Learn how to use Tachyons to craft beautiful, responsive, functional and fast UI with minimal CSS
- [Tachyons TLDR](https://tachyons-tldr.now.sh/#/classes): Quick lookup for Tachyons classes, scales and color palette
- [Tachyons Pro](https://tachyons.pro/): Fun quiz for memorizing class names
