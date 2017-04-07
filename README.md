# api documentation for  [gulp-jsdoc (v0.1.5)](https://github.com/jsBoot/gulp-jsdoc)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-jsdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-jsdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-jsdoc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-jsdoc)
#### A jsdoc plugin for Gulp

[![NPM](https://nodei.co/npm/gulp-jsdoc.png?downloads=true)](https://www.npmjs.com/package/gulp-jsdoc)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-jsdoc/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-gulp-jsdoc%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-jsdoc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-jsdoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-jsdoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mangled Deutz",
        "email": "olivier@webitup.fr",
        "url": "https://github.com/dmp42"
    },
    "bugs": {
        "url": "https://github.com/jsBoot/gulp-jsdoc/issues",
        "email": "dev@webitup.fr"
    },
    "contributors": [],
    "dependencies": {
        "chalk": "~0.4.0",
        "gulp-util": "~2.2.14",
        "ink-docstrap": "~0.4.5",
        "jsdoc": "3.3.0-alpha5",
        "marked": "~0.3.1",
        "taffydb": "~2.7.2",
        "text-table": "~0.2.0",
        "through2": "^1.0.0",
        "vinyl-fs": "~0.3.0",
        "wrench": "~1.5.6"
    },
    "deprecated": "This project is deprecated. Use gulp-jsdoc3 instead.",
    "description": "A jsdoc plugin for Gulp",
    "devDependencies": {
        "coveralls": "^2.7.1",
        "event-stream": "~3.1.0",
        "gulp": "^3.5.6",
        "gulp-eslint": "~0.1.2",
        "gulp-jshint": "^1.3.4",
        "gulp-template": "~0.1.1",
        "istanbul": "^0.2.4",
        "jshint": "^2.4.4",
        "jshint-stylish": "^0.1.5",
        "mocha": "^1.17.1",
        "mocha-lcov-reporter": "~0.0.1",
        "should": "^3.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "c79e06f9bdeb868a3e096fa56da037110d998455",
        "tarball": "https://registry.npmjs.org/gulp-jsdoc/-/gulp-jsdoc-0.1.5.tgz"
    },
    "engines": {
        "node": ">=0.10.0",
        "npm": ">=1.0.0"
    },
    "gitHead": "8a6d325c354237e1a69019fb7b19f3790cdbde04",
    "homepage": "https://github.com/jsBoot/gulp-jsdoc",
    "keywords": [
        "gulpplugin",
        "jsdoc",
        "documentation",
        "javascript",
        "gulp"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "dmp",
            "email": "olivier@webitup.fr"
        },
        {
            "name": "indexzero",
            "email": "charlie.robbins@gmail.com"
        }
    ],
    "name": "gulp-jsdoc",
    "optionalDependencies": {},
    "private": false,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/jsBoot/gulp-jsdoc.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "0.1.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-jsdoc](#apidoc.module.gulp-jsdoc)



# <a name="apidoc.module.gulp-jsdoc"></a>[module gulp-jsdoc](#apidoc.module.gulp-jsdoc)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
