# npmdoc-markdown-to-html

#### basic api documentation for  [markdown-to-html (v0.0.13)](https://github.com/cwjohan/markdown-to-html)  [![npm package](https://img.shields.io/npm/v/npmdoc-markdown-to-html.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-markdown-to-html) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-markdown-to-html.svg)](https://travis-ci.org/npmdoc/node-npmdoc-markdown-to-html)

#### Converts markdown text to HTML. A readable stream plus utilities and web demo.

[![NPM](https://nodei.co/npm/markdown-to-html.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/markdown-to-html)

- [https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Craig Johannsen"
    },
    "bin": {
        "markdown": "./bin/markdown",
        "markdownb": "./bin/markdownb",
        "github-markdown": "./bin/github-markdown",
        "github-markdownb": "./bin/github-markdownb"
    },
    "bugs": {
        "url": "https://github.com/cwjohan/markdown-to-html/issues"
    },
    "dependencies": {
        "gfm-linkify": "^0.1.0",
        "marked": "^0.3.2",
        "open": "0.0.5",
        "pygmentize-bundled": "^2.2.0",
        "request": "^2.47.0",
        "tmp": "0.0.24",
        "yargs": "^1.3.3"
    },
    "description": "Converts markdown text to HTML. A readable stream plus utilities and web demo.",
    "devDependencies": {
        "errorhandler": "1.1.x",
        "express": "4.6.x",
        "jade": "1.4.x",
        "method-override": "2.1.x",
        "morgan": "1.5.x",
        "serve-favicon": "2.0.x",
        "stylus": "0.47.x"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "003467759db8b319b06c1d9f092072eb44177f4d",
        "tarball": "https://registry.npmjs.org/markdown-to-html/-/markdown-to-html-0.0.13.tgz"
    },
    "gitHead": "324d2924c6193b4ef60d61098fe739b1d2fba21f",
    "homepage": "https://github.com/cwjohan/markdown-to-html",
    "keywords": [
        "markdown",
        "markdown-to-html",
        "html",
        "render",
        "convert",
        "stream",
        "pipe"
    ],
    "license": "MIT",
    "main": "markdown.js",
    "maintainers": [
        {
            "name": "cwjohan"
        }
    ],
    "name": "markdown-to-html",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/cwjohan/markdown-to-html.git"
    },
    "scripts": {
        "clean": "bash script/clean",
        "start": "bash script/web-demo",
        "test": "bash script/test"
    },
    "version": "0.0.13"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
