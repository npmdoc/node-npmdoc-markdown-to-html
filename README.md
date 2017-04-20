# npmdoc-markdown-to-html

#### api documentation for  [markdown-to-html (v0.0.13)](https://github.com/cwjohan/markdown-to-html)  [![npm package](https://img.shields.io/npm/v/npmdoc-markdown-to-html.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-markdown-to-html) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-markdown-to-html.svg)](https://travis-ci.org/npmdoc/node-npmdoc-markdown-to-html)

#### Converts markdown text to HTML. A readable stream plus utilities and web demo.

[![NPM](https://nodei.co/npm/markdown-to-html.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/markdown-to-html)

- [https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "markdown-to-html",
    "version": "0.0.13",
    "description": "Converts markdown text to HTML. A readable stream plus utilities and web demo.",
    "main": "markdown.js",
    "bin": {
        "markdown": "./bin/markdown",
        "markdownb": "./bin/markdownb",
        "github-markdown": "./bin/github-markdown",
        "github-markdownb": "./bin/github-markdownb"
    },
    "preferGlobal": true,
    "scripts": {
        "test": "bash script/test",
        "clean": "bash script/clean",
        "start": "bash script/web-demo"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/cwjohan/markdown-to-html"
    },
    "keywords": [
        "markdown",
        "markdown-to-html",
        "html",
        "render",
        "convert",
        "stream",
        "pipe"
    ],
    "author": "Craig Johannsen",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/cwjohan/markdown-to-html/issues"
    },
    "homepage": "https://github.com/cwjohan/markdown-to-html",
    "dependencies": {
        "gfm-linkify": "^0.1.0",
        "marked": "^0.3.2",
        "open": "0.0.5",
        "pygmentize-bundled": "^2.2.0",
        "request": "^2.47.0",
        "tmp": "0.0.24",
        "yargs": "^1.3.3"
    },
    "directories": {
        "test": "test"
    },
    "devDependencies": {
        "errorhandler": "1.1.x",
        "express": "4.6.x",
        "jade": "1.4.x",
        "method-override": "2.1.x",
        "morgan": "1.5.x",
        "serve-favicon": "2.0.x",
        "stylus": "0.47.x"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
