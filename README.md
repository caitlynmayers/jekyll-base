Jekyll Base
===========

A starter project with a full setup for Jekyll with GulpJS, SASS, Image Minification, AutoPrefixer &amp; BrowserSync. This repo is based on [this starter project by Shaky Shane](https://github.com/shakyShane/jekyll-gulp-sass-browser-sync).

## System Preparation

Before using this starter project, you'll need to have the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll`
2. [NodeJS](http://nodejs.org) - I recommend using [Homebrew](http://brew.sh/) to install this.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp` (mac users may need sudo)

### Dependencies
1. Gulp
2. BrowserSync
3. Gulp Sass
4. Gulp Autoprefixer 
5. [Gulp Imagemin](https://www.npmjs.com/package/imagemin-pngquant) - `$ npm install --save-dev gulp-imagemin`
6. [Imagemin PNGQuant](https://www.npmjs.com/package/gulp-imagemin) - ``$ npm install --save-dev imagemin-pngquant `

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.

```shell
$ gulp
```

**jekyll**

As this is just a Jekyll project, you can use any of the commands listed in their [docs](http://jekyllrb.com/docs/usage/)