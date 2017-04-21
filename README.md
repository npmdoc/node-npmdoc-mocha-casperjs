# npmdoc-mocha-casperjs

#### api documentation for  mocha-casperjs (v0.6.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-mocha-casperjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mocha-casperjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mocha-casperjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mocha-casperjs)

#### Write CasperJS tests using Mocha

[![NPM](https://nodei.co/npm/mocha-casperjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mocha-casperjs)

- [https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mocha-casperjs",
    "description": "Write CasperJS tests using Mocha",
    "keywords": [
        "mocha",
        "casperjs",
        "bdd",
        "phantomjs",
        "testing"
    ],
    "version": "0.6.0",
    "author": "Nathan Black <nathan@nathanblack.org>",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/nathanboktae/mocha-casperjs"
    },
    "readmeFilename": "Readme.md",
    "bugs": {
        "url": "http://github.com/nathanboktae/mocha-casperjs/issues"
    },
    "main": "mocha-casperjs.js",
    "bin": {
        "mocha-casperjs": "./bin/mocha-casperjs"
    },
    "peerDependencies": {
        "mocha": ">= 1.14.0",
        "casperjs": ">= 1.1.0-beta3"
    },
    "devDependencies": {
        "chai": "3",
        "coffee-script": "1.7.x",
        "casper-chai": ">= 0.1.6",
        "mocha": "2",
        "casperjs": "git://github.com/n1k0/casperjs.git#master",
        "phantomjs": "^1.9.1"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha test/all.coffee"
    },
    "directories": {
        "test": "test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
