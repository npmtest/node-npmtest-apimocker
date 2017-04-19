# npmtest-apimocker

#### test coverage for  [apimocker (v0.5.0)](https://github.com/gstroup/apimocker#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-apimocker.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-apimocker) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-apimocker.svg)](https://travis-ci.org/npmtest/node-npmtest-apimocker)

#### Simple HTTP server that returns mock service API responses to your front end.

[![NPM](https://nodei.co/npm/apimocker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apimocker)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-apimocker/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-apimocker/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-apimocker/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-apimocker/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-apimocker/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-apimocker/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-apimocker/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-apimocker/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-apimocker/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-apimocker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-apimocker/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-apimocker/build/test-report.html](https://npmtest.github.io/node-npmtest-apimocker/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-apimocker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-apimocker/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-apimocker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apimocker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apimocker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apimocker/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-apimocker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-apimocker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Greg Stroup"
    },
    "bin": {
        "apimocker": "./bin/apimocker.js"
    },
    "bugs": {
        "url": "https://github.com/gstroup/apimocker/issues"
    },
    "dependencies": {
        "JSONPath": ">=0.10.0",
        "body-parser": "~1.4.3",
        "commander": ">=1",
        "express": "~4.5",
        "express-http-proxy": ">=0.7.0",
        "express-xml-bodyparser": "^0.2.2",
        "underscore": ">=1",
        "untildify": "^2.0.0"
    },
    "description": "Simple HTTP server that returns mock service API responses to your front end.",
    "devDependencies": {
        "chai": ">=1.5.0",
        "grunt": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-watch": ">=0.3.1",
        "grunt-mocha-cli": "^2.1.0",
        "mocha": ">=1.8.2",
        "sinon": ">=1.6.0",
        "supertest": "^1.2.0"
    },
    "directories": {
        "bin": "./bin",
        "lib": "./lib",
        "test": "./test",
        "samplemocks": "./samplemocks"
    },
    "dist": {
        "shasum": "46f8236c83fe90c81a85636dc39d1c0bb18922d9",
        "tarball": "https://registry.npmjs.org/apimocker/-/apimocker-0.5.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "98efced6627f1c6325ecc35626562f68959bedc3",
    "homepage": "https://github.com/gstroup/apimocker#readme",
    "keywords": [
        "express",
        "mock",
        "stub",
        "REST",
        "SOAP",
        "testing",
        "functional",
        "api",
        "grunt",
        "gulp"
    ],
    "license": "MIT",
    "main": "./lib/apimocker.js",
    "maintainers": [
        {
            "name": "gstroup"
        }
    ],
    "name": "apimocker",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gstroup/apimocker.git"
    },
    "scripts": {
        "start": "node bin/apimocker.js -c config.json",
        "test": "mocha test/*.js"
    },
    "version": "0.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
