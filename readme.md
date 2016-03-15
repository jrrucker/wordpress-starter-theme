# Starter WordPress Theme

This starter theme is a basic WordPress theme I created to quickly start development on new themes while I was working at NC State.  SInce then, I've made some modiications to generalize it for wider use.  There isn't much to it except a basic theme structure, a Grunt task for CSS compilation and JavaScript minification, and few common dependencies like JQuery and Bootstrap. Feel free to fork and modify it as you please under the MIT license.

## Get Started

1. [Install Node.js](https://nodejs.org/en/download/)
1. Run `npm install -g bower` to install Bower.
1. Run `npm install -g grunt-cli` to install the Grunt command line interface.
1. Run `./scripts/refresh.sh` to install dependencies, and clean up stale dependencies and build files.
1. Run `grunt` to compile CSS and add watcher for changes to CSS and JavaScript.

## MIT License

Copyright (c) 2016 Josh Rucker

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
