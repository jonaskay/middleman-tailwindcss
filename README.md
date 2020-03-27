# Middleman + Tailwind CSS
[![Build Status](https://travis-ci.com/jonaskay/middleman-tailwindcss.svg?branch=master)](https://travis-ci.com/jonaskay/middleman-tailwindcss)
## About

This is a project template for the [Middleman Static Site Generator](https://middlemanapp.com/) with [Tailwind CSS](https://tailwindcss.com/) and [gulp](https://gulpjs.com/). It is based on the [
Default Middleman Project Template](https://github.com/middleman/middleman-templates-default).

## Included Libraries

* [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
* [gulp](https://gulpjs.com/) - A JavaScript toolkit
* [PostCSS](http://postcss.org/) - A tool for automating CSS operations
* [PostCSS-cssnext](http://cssnext.io/) - A PostCSS plugin to use tomorrow's CSS syntax, today
* [PostCSS-import](https://github.com/postcss/postcss-import) - A PostCSS plugin to inline @import rules content

## Getting Started

### Requirements

* [Middleman 4.x](https://middlemanapp.com/basics/install/)
* [Ruby](https://www.ruby-lang.org/en/)
* [Bundler](http://bundler.io/)
* [Node.js](https://nodejs.org/en/)

### Start a New Project

Start a new Middleman project using this template:

`$ middleman init mysite -T jonaskay/middleman-tailwindcss`

Change into the project root:

`$ cd mysite`

Install dependencies:

```
# Using npm
$ npm install

# Using Yarn
$ yarn install
```

Add the project to version control (recommended, not required):

```
$ git init
$ git add .
$ git commit -m "Initial commit"
```

## Useful Commands

Run the development server:

`bundle exec middleman server`

Build your site:

`bundle exec middleman build`

## Acknowledgements

This project template uses code from the following libraries:
* <https://github.com/middleman/middleman-templates-default>

The following repositories have been helpful in setting up this project:
* <https://github.com/joshukraine/middleman-gulp>
