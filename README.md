# api documentation for  [markdown-to-html (v0.0.13)](https://github.com/cwjohan/markdown-to-html)  [![npm package](https://img.shields.io/npm/v/npmdoc-markdown-to-html.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-markdown-to-html) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-markdown-to-html.svg)](https://travis-ci.org/npmdoc/node-npmdoc-markdown-to-html)
#### Converts markdown text to HTML. A readable stream plus utilities and web demo.

[![NPM](https://nodei.co/npm/markdown-to-html.png?downloads=true)](https://www.npmjs.com/package/markdown-to-html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-markdown-to-html_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-markdown-to-html/build/apidoc.html)

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
            "name": "cwjohan",
            "email": "cwjohan@gmail.com"
        }
    ],
    "name": "markdown-to-html",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module markdown-to-html](#apidoc.module.markdown-to-html)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.</span>GithubMarkdown ()](#apidoc.element.markdown-to-html.GithubMarkdown)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.</span>Markdown ()](#apidoc.element.markdown-to-html.Markdown)
1.  object <span class="apidocSignatureSpan">markdown-to-html.</span>GithubMarkdown.prototype
1.  object <span class="apidocSignatureSpan">markdown-to-html.</span>Markdown.prototype

#### [module markdown-to-html.GithubMarkdown](#apidoc.module.markdown-to-html.GithubMarkdown)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.</span>GithubMarkdown ()](#apidoc.element.markdown-to-html.GithubMarkdown.GithubMarkdown)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.GithubMarkdown.</span>super_ (options)](#apidoc.element.markdown-to-html.GithubMarkdown.super_)

#### [module markdown-to-html.GithubMarkdown.prototype](#apidoc.module.markdown-to-html.GithubMarkdown.prototype)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.GithubMarkdown.prototype.</span>_read (size)](#apidoc.element.markdown-to-html.GithubMarkdown.prototype._read)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.GithubMarkdown.prototype.</span>cat (data)](#apidoc.element.markdown-to-html.GithubMarkdown.prototype.cat)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.GithubMarkdown.prototype.</span>render (fileName, opts, onDone)](#apidoc.element.markdown-to-html.GithubMarkdown.prototype.render)

#### [module markdown-to-html.Markdown](#apidoc.module.markdown-to-html.Markdown)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.</span>Markdown ()](#apidoc.element.markdown-to-html.Markdown.Markdown)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.Markdown.</span>super_ (options)](#apidoc.element.markdown-to-html.Markdown.super_)

#### [module markdown-to-html.Markdown.prototype](#apidoc.module.markdown-to-html.Markdown.prototype)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.Markdown.prototype.</span>_read (size)](#apidoc.element.markdown-to-html.Markdown.prototype._read)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.Markdown.prototype.</span>cat (data)](#apidoc.element.markdown-to-html.Markdown.prototype.cat)
1.  [function <span class="apidocSignatureSpan">markdown-to-html.Markdown.prototype.</span>render (fileName, opts, onDone)](#apidoc.element.markdown-to-html.Markdown.prototype.render)



# <a name="apidoc.module.markdown-to-html"></a>[module markdown-to-html](#apidoc.module.markdown-to-html)

#### <a name="apidoc.element.markdown-to-html.GithubMarkdown"></a>[function <span class="apidocSignatureSpan">markdown-to-html.</span>GithubMarkdown ()](#apidoc.element.markdown-to-html.GithubMarkdown)
- description and source-code
```javascript
function GithubMarkdown() {
  this.super_ = this.constructor.super_;
  this.super_.call(this);
  this.debug = false;
  this.bufmax = 1024;
  this.html = '';
  this.setEncoding('utf8');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.markdown-to-html.Markdown"></a>[function <span class="apidocSignatureSpan">markdown-to-html.</span>Markdown ()](#apidoc.element.markdown-to-html.Markdown)
- description and source-code
```javascript
function Markdown() {
  this.super_ = this.constructor.super_;
  this.super_.call(this);
  this.debug = false;
  this.bufmax = 1024;
  this.html = '';
  this.setEncoding('utf8');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.markdown-to-html.GithubMarkdown"></a>[module markdown-to-html.GithubMarkdown](#apidoc.module.markdown-to-html.GithubMarkdown)

#### <a name="apidoc.element.markdown-to-html.GithubMarkdown.GithubMarkdown"></a>[function <span class="apidocSignatureSpan">markdown-to-html.</span>GithubMarkdown ()](#apidoc.element.markdown-to-html.GithubMarkdown.GithubMarkdown)
- description and source-code
```javascript
function GithubMarkdown() {
  this.super_ = this.constructor.super_;
  this.super_.call(this);
  this.debug = false;
  this.bufmax = 1024;
  this.html = '';
  this.setEncoding('utf8');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.markdown-to-html.GithubMarkdown.super_"></a>[function <span class="apidocSignatureSpan">markdown-to-html.GithubMarkdown.</span>super_ (options)](#apidoc.element.markdown-to-html.GithubMarkdown.super_)
- description and source-code
```javascript
function Readable(options) {
  if (!(this instanceof Readable))
    return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  if (options && typeof options.read === 'function')
    this._read = options.read;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.markdown-to-html.GithubMarkdown.prototype"></a>[module markdown-to-html.GithubMarkdown.prototype](#apidoc.module.markdown-to-html.GithubMarkdown.prototype)

#### <a name="apidoc.element.markdown-to-html.GithubMarkdown.prototype._read"></a>[function <span class="apidocSignatureSpan">markdown-to-html.GithubMarkdown.prototype.</span>_read (size)](#apidoc.element.markdown-to-html.GithubMarkdown.prototype._read)
- description and source-code
```javascript
_read = function (size) {
  var pushSize = Math.min(size, this.bufmax);
  if (this.html.length > 0) {
    if (this.debug) console.error('>>>_read size=' + pushSize + ', html="' + this.html.substr(0, pushSize) + '"');
    this.push(this.html.substr(0, pushSize));
    this.html = this.html.slice(pushSize);
    if (this.done && this.html.length === 0) {
      this.push(null); // eof
    }
  } else {
    if (this.debug) console.error('>>>_read - nothing to push');
  }
  return;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.markdown-to-html.GithubMarkdown.prototype.cat"></a>[function <span class="apidocSignatureSpan">markdown-to-html.GithubMarkdown.prototype.</span>cat (data)](#apidoc.element.markdown-to-html.GithubMarkdown.prototype.cat)
- description and source-code
```javascript
cat = function (data) {
  this.html += data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.markdown-to-html.GithubMarkdown.prototype.render"></a>[function <span class="apidocSignatureSpan">markdown-to-html.GithubMarkdown.prototype.</span>render (fileName, opts, onDone)](#apidoc.element.markdown-to-html.GithubMarkdown.prototype.render)
- description and source-code
```javascript
render = function (fileName, opts, onDone) {
  if (this.debug) console.error('>>>rendering...');
  var flavor     = opts.flavor || 'markdown',
      context    = opts.context,
      stylesheet = opts.stylesheet,
      userName   = opts.username || 'request',
      title      = opts.title,
      titleText  = title;

  if (title) {
    var dirName  = path.dirname(fileName),
        baseName = path.basename(fileName),
        pathName = path.resolve(fileName);
    titleText = titleText.replace('$FILENAME', fileName);
    titleText = titleText.replace('$DIRNAME',  dirName);
    titleText = titleText.replace('$BASENAME', baseName);
    titleText = titleText.replace('$PATHNAME', pathName);
  }

  this.done = false;

  this.once('error', function(err) {
    if (onDone) onDone(err)
    else console.error('>>>' + err);
  });

  if (! fileName) {
    console.log('Missing file name arg');
    process.exit();
  }

  //======================================================
  // Read the file content.
  //======================================================
  fs.readFile(fileName, onFileReady.bind(this));

  //======================================================
  // Process the file content.
  //======================================================
  function onFileReady(err, data) {
    if (err) {
      if (onDone) onDone(err)
      else console.error('>>>' + err);
      return;
    }

    var fileContent = data.toString();

    var msg = {
      text:    fileContent,
      mode:    flavor,
      context: context
    };

    var jsonMsg = JSON.stringify(msg);

    var options = {
      method: 'POST',
      preambleCRLF: true,
      postambleCRLF: true,
      uri: 'https://api.github.com/markdown',
      'content-type': 'application/json',
      headers: {
        'User-Agent' : userName
      },
      body: jsonMsg
    };

    //=======================================================
    // Call the Github Markdown API to parse the file content
    //=======================================================
    request(options, handleResponse.bind(this));

    //======================================================
    // Enhance the output of the Github Markdown API with
    // optional header or trailer.
    //======================================================
    function handleResponse(err, response, body) {
      if (this.debug) console.error('>>>handling response...');
      if (err) {
        if (onDone) onDone(err)
        else console.error('>>>upload to github failed: ', err);
        return;
      }

      if (stylesheet || title) {
        if (titleText == null) titleText = fileName;
        this.cat('<!DOCTYPE html>\n' +
                 '<html>\n' +
                 '<head>\n' +
                 '  <title>' + titleText + '</title>\n' +
                 '  <link rel="stylesheet" href="' + stylesheet + '">\n' +
                 '</head>\n' +
                 '<body>\n' );
      }

      this.cat(body);
      this.cat('\n');

      if (stylesheet || title) {
        this.cat( '</body>\n</html>\n' );
      }

      if (this.debug) console.error('>>>finished getting code');
      this.done = true;
      if (onDone) onDone();
    } // end handleResponse
  } // end onFileReady
}
```
- example usage
```shell
...
...
// Write a header.
console.log('===============================');
// Write a trailer at eof.
md.once('end', function() {
  console.log('===============================');
});
md.render(fileName, opts, function(err) {
  if (err) {
    console.error('>>>' + err);
    process.exit();
  }
  md.pipe(process.stdout);
});
'''
...
```



# <a name="apidoc.module.markdown-to-html.Markdown"></a>[module markdown-to-html.Markdown](#apidoc.module.markdown-to-html.Markdown)

#### <a name="apidoc.element.markdown-to-html.Markdown.Markdown"></a>[function <span class="apidocSignatureSpan">markdown-to-html.</span>Markdown ()](#apidoc.element.markdown-to-html.Markdown.Markdown)
- description and source-code
```javascript
function Markdown() {
  this.super_ = this.constructor.super_;
  this.super_.call(this);
  this.debug = false;
  this.bufmax = 1024;
  this.html = '';
  this.setEncoding('utf8');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.markdown-to-html.Markdown.super_"></a>[function <span class="apidocSignatureSpan">markdown-to-html.Markdown.</span>super_ (options)](#apidoc.element.markdown-to-html.Markdown.super_)
- description and source-code
```javascript
function Readable(options) {
  if (!(this instanceof Readable))
    return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  if (options && typeof options.read === 'function')
    this._read = options.read;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.markdown-to-html.Markdown.prototype"></a>[module markdown-to-html.Markdown.prototype](#apidoc.module.markdown-to-html.Markdown.prototype)

#### <a name="apidoc.element.markdown-to-html.Markdown.prototype._read"></a>[function <span class="apidocSignatureSpan">markdown-to-html.Markdown.prototype.</span>_read (size)](#apidoc.element.markdown-to-html.Markdown.prototype._read)
- description and source-code
```javascript
_read = function (size) {
  var pushSize = Math.min(size, this.bufmax);
  if (this.html.length > 0) {
    if (this.debug) console.error('>>>_read size=' + pushSize + ', html="' + this.html.substr(0, pushSize) + '"');
    this.push(this.html.substr(0, pushSize));
    this.html = this.html.slice(pushSize);
    if (this.done && this.html.length === 0) {
      this.push(null); // eof
    }
  } else {
    if (this.debug) console.error('>>>_read - nothing to push');
  }
  return;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.markdown-to-html.Markdown.prototype.cat"></a>[function <span class="apidocSignatureSpan">markdown-to-html.Markdown.prototype.</span>cat (data)](#apidoc.element.markdown-to-html.Markdown.prototype.cat)
- description and source-code
```javascript
cat = function (data) {
  this.html += data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.markdown-to-html.Markdown.prototype.render"></a>[function <span class="apidocSignatureSpan">markdown-to-html.Markdown.prototype.</span>render (fileName, opts, onDone)](#apidoc.element.markdown-to-html.Markdown.prototype.render)
- description and source-code
```javascript
render = function (fileName, opts, onDone) {
  var flavour    = opts.flavor || 'gfm',
      highlight  = opts.highlight,
      stylesheet = opts.stylesheet,
      context    = opts.context,
      title      = opts.title,
      titleText  = title;

  if (title) {
    var dirName  = path.dirname(fileName),
        baseName = path.basename(fileName),
        pathName = path.resolve(fileName);
    titleText = titleText.replace('$FILENAME', fileName);
    titleText = titleText.replace('$DIRNAME',  dirName);
    titleText = titleText.replace('$BASENAME', baseName);
    titleText = titleText.replace('$PATHNAME', pathName);
  }

  this.done = false;

  this.once('error', function(err) {
    if (onDone) onDone(err)
    else console.error('>>>' + err);
  });

  if (fileName === null) {
    if (onDone) onDone('Missing file name arg');
    else console.error('>>>Missing file name arg');
  }

  //======================================================
  // Read the file content.
  //======================================================
  fs.readFile(fileName, onFileReady.bind(this));

  //======================================================
  // Process the file content.
  //======================================================
  function onFileReady(err, data) {
    if (err) {
      if (onDone) onDone(err);
      else console.error('>>>' + err);
      return;
    }

    var fileContent = data.toString();

    var options = {
      gfm: (flavour === 'gfm') ? true : false,
      breaks: true,
      tables: true,
      sanitize: true
    };

    if (highlight) {
      options['highlight'] = function(code, lang, callback) {
        pygmentize({lang: lang, format: 'html'}, code, function(err, result) {
          if (err) {
            callback(err);
          }
          callback(err, result.toString());
        });
      }
    }

    //======================================================
    // Call marked to parse the file content
    //======================================================
    if (this.debug) console.error('>>>starting to get code');
    try {
      marked.setOptions(options);
      marked(fileContent, getCode.bind(this));
    } catch(err) {
      if (onDone) onDone(err)
      else console.error('>>>' + err);
    }

    //======================================================
    // Enhance the output of marked with optional header
    // or trailer. Linkify if context specified.
    //======================================================
    function getCode(err, code) {
      if (err) {
        if (onDone) onDone(err)
        else console.error('>>>' + err);
        return;
      }
      if (stylesheet || title) {
        if (titleText == null) titleText = fileName;
        this.cat('<!DOCTYPE html>\n' +
                 '<html>\n' +
                 '<head>\n' +
                 '  <title>' + titleText + '</title>\n');
        if (stylesheet) {
          this.cat('  <link rel="stylesheet" href="' + stylesheet + '">\n');
        }
        this.cat('</head>\n<body>\n' );
      }

      if (context) {
        this.cat( linkify(code, context) );
      } else {
        this.cat( code );
      }

      if (stylesheet || title) {
        this.cat( '</body>\n</html>\n' );
      }
      if (this.debug) console.error('>>>finished getting code');
      this.done = true;
      if (onDone) onDone();
    } // end getCode
  } // end onFileReady
}
```
- example usage
```shell
...
...
// Write a header.
console.log('===============================');
// Write a trailer at eof.
md.once('end', function() {
  console.log('===============================');
});
md.render(fileName, opts, function(err) {
  if (err) {
    console.error('>>>' + err);
    process.exit();
  }
  md.pipe(process.stdout);
});
'''
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
