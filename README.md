dummy
=====

A light Sass &amp; coffee front-end base


# Usage

Go check the Yeoman's [generator](https://github.com/in8/generator-dummy) !

# Features

- A full css light grid system
- A simple font sizing : 1.6em = 16px;
- An unit based margin & padding system
- A collection of variables to manage default sizing, fonts and colors
- A background-size fallback for Internet Explorer
- Some jQuery plugins helpers ready to use


# To discuss

## CSS

- mediaqueries in a separate file / inline in the main sheet
- usage of size unit ($u) : function(value) / value*$u
- gutter multiple of $u
- use .column + .column to handle margins in grid

## HTML

- Use of templates ?


# Release notes

- **0.9.0** : *Dummy* is dead, long live *generator-dummy*
- **0.8.3** : Removed generated documentation from repository
- **0.8.2** : Added notifications to tasks
- **0.8.1** : fixed a regression from 0.8.0
- **0.8.0** :
  - Changed server task to serve (best practice)
  - Switched default port to 0 to enable simple multiple server running simultaneously
- **0.7.0** :    Documentation build is now automated
- **0.6.1** :    Moved examples from index.html to demo/index.html
- **0.6.0** :
  - Removed livereload script from html, you must use a browser extension listenning port 35729
  - Until generator is built, a gruntFile for typo3 has been added
- **0.5.1** :    Improved documentation
- **0.5.0** :    Sourcemapping for sass & coffescript files enabled
- **0.3.0** :    Vendors prefixe are now automatically added to the main.css file
- **0.4.0** :    The default grunt task now build coffeescript annotated sources
- **0.2.0** :    Reworked grid system : You can now use *class="column column-value"* in any wrapper to get your columns right
- **0.1.0** :    First Sass & Coffe version of the Dummy


# Road map

- before **1.0.0** : solve discussions questions and implement them
- **1.0.1** : rewrite CoffeScript
- **1.1.0** : add a dynamic demo for grid system
- **1.2.0** : Add imagemin to handle optimization


- Write Inouit's coding guidelines
- Keep improving the grid system


#Kown issues


# Tree

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
     └─ rte.css
    js
     └─ components
     └─ htc
         └─ backgroundsize.min.htc
     └─ src
         └─ base.coffee
         └─ main.coffee
    index.html
    bower.json
    LICENCE
    README.md
    .bowerrc
    .editorconfig
    .gitignore