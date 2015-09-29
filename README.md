# Gulp starter

## Instructions

1. Make sure you have these installed
    - [node.js](http://nodejs.org/)
    - [git](http://git-scm.com/)
    - [gulp](http://gulpjs.com/)
    - [ruby](http://gulpjs.com/)

2. Clone this repository into your local machine using the terminal (mac) or Gitbash (PC) `> git@github.com:eckzen/starter.git`
3. CD to the folder `cd starter`
4. Run `> npm-install` to install the project dependencies
5. Install gulp.js via the Mac terminal or Gitbash on a PC `> npm install -g gulp`
6. Run the Gulp command `> gulp`

##If i am going to create a new gulp from scratch

Create a folder

    mkdir new_folder

Go to that folder

    cd new_folder

Create a package JSON

    npm init            #this will create a package json

For first time install Gulp

    npm install -g gulp

Install gulp in local folder

    npm install --save-dev gulp

*it will add gulp as a dependency in package json*

Install other packages

    npm install --save-dev gulp gulp-jshint gulp-ruby-sass gulp-sourcemaps gulp-webserver 

Create a gulpfile.js file

Create a .gitignore file

Create a .jshintrc file

In the browser

    localhost:8000

##Folder structure

+ gulpfile.js
+ package.json
+ README.md
+ .gitignore
+ .jshintrc
+ node_modules
+ sass
    * modules
    * style.scss
    * _base.scss
    * _interface.scss
    * _mixins.scss
    * _normalize.scss
    * _variables.scss
+ builds
    * index.html
    * images
    * css
        - style.css
    * js
        - script.js



