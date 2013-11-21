dummy
=====

A light Sass &amp; coffee front-end base


# Usage

- Clone
- remove .git folder
- add *node_modules* & *\_bower\_components* folders to project .gitignore
- run *npm install && bower install*
- move needed minified components from *\_bower\_components* to *components*
  - jQuery & Modernizr are needed
- grunt server
- work


# To discuss

## CSS

- mediaqueries in a separate file / inline in the main sheet
- usage of size unit ($u) : function(value) / value*$u


# Road map

- 1.0.0 : create a clean index.html & move test page in an demo/example folder
- 1.0.1 : rewrite CoffeScript
- 1.0.2 : fix the doc task bug (breaking the chain of tasks)
- 1.1.1 : add a dynamic demo for grid system
- 2.0.0 : make it a generator whith dependencies and optionnal components
- 2.1.0 : custom Modernizr build


#Kown issues

- To build annotated sources for Sass files you need to run *grunt docco:buildSass*
- To build annotated sources for CoffeeScript files you need to run *grunt docco:buildCoffee*


# tree

_generated files*_

    css
     └─ src
         └─ columns.scss
         └─ config.scss
         └─ functions.scss
         └─ mixins.scss
         └─ ie.scss
         └─ main.scss
         └─ mediaqueries.scss
         └─ powermail.scss
         └─ reset.scss
         └─ styles.scss
     └─ ie.css*
     └─ main.css*
     └─ rte.css
    docs
    img
    js
     └─ components
     └─ htc
         └─ backgroundsize.min.htc
     └─ src
         └─ base.coffee
         └─ min.coffee
     └─ main.js*
    index.html
    bower.json
    gruntfile.coffee
    package.josn
    LICENCE
    README.md
    .bowerrc
    .editorconfig
    .gitignore

# Dependencies

The build and serve tasks use the plugin *grunt-contrib-sass*, it requires you to have *Ruby* and *Sass* installed.
The sourcemap generator requires *Sass 3.3.0*, which can be installed with *gem install sass --pre*

