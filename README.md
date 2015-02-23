reveal-template
===============

#OPI Reveal.js Template with new logos

![Example slide 1](https://raw.githubusercontent.com/erickinsella/reveal-template/master/dist/assets/img/opi-revealjs-template.jpg)

![Example slide 2](https://raw.githubusercontent.com/erickinsella/reveal-template/master/dist/assets/img/opi-revealjs-template2.jpg)


## Dependencies
* Node
* Bower

##Getting Started
* Run `npm install` to install node dependencies
* Run `bower install` to install client-side dependencies

##Grunt Commands
* `grunt assemble`
  * Minify/uglify the javascript source and css
  * Compiles jade
  * Stages everything in the dist folder
* `grunt run`
  * Starts a server running on port 8000
  * watches for changes on project files
  * When files change, the assemble task is re-run and
  * Livereload triggers browser update on assemble task completion
* `grunt publish`
  * Publishes slides to GitHub pages
  * Uses git subtree merge to merge the contents of dist into the gh-pages branch
