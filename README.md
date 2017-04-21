# npmdoc-jpegoptim-bin

#### api documentation for  jpegoptim-bin (v3.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-jpegoptim-bin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jpegoptim-bin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jpegoptim-bin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jpegoptim-bin)

#### jpegoptim wrapper that makes it seamlessly available as a local dependency

[![NPM](https://nodei.co/npm/jpegoptim-bin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jpegoptim-bin)

- [https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jpegoptim-bin",
    "version": "3.0.0",
    "description": "jpegoptim wrapper that makes it seamlessly available as a local dependency",
    "license": "MIT",
    "repository": "imagemin/jpegoptim-bin",
    "author": {
        "name": "1000ch",
        "url": "http://github.com/1000ch"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "bin": {
        "jpegoptim": "cli.js"
    },
    "scripts": {
        "postinstall": "node lib/install.js",
        "test": "xo && mocha --timeout 50000"
    },
    "files": [
        "cli.js",
        "index.js",
        "lib"
    ],
    "keywords": [
        "compress",
        "image",
        "img",
        "jpeg",
        "jpg",
        "minify",
        "optimize"
    ],
    "dependencies": {
        "bin-build": "^2.0.0",
        "bin-wrapper": "^3.0.0",
        "logalot": "^2.0.0"
    },
    "devDependencies": {
        "bin-check": "^1.0.0",
        "compare-size": "^1.0.1",
        "mkdirp": "^0.5.0",
        "mocha": "^2.2.4",
        "rimraf": "^2.3.2",
        "xo": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
