# npmtest-paypal-rest-sdk

#### basic test coverage for  [paypal-rest-sdk (v1.7.1)](https://github.com/paypal/PayPal-node-SDK)  [![npm package](https://img.shields.io/npm/v/npmtest-paypal-rest-sdk.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-paypal-rest-sdk) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-paypal-rest-sdk.svg)](https://travis-ci.org/npmtest/node-npmtest-paypal-rest-sdk)

#### SDK for PayPal REST APIs

[![NPM](https://nodei.co/npm/paypal-rest-sdk.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/paypal-rest-sdk)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-paypal-rest-sdk/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-paypal-rest-sdk/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/test-report.html](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-paypal-rest-sdk/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-paypal-rest-sdk/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-paypal-rest-sdk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-paypal-rest-sdk/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-paypal-rest-sdk/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "PayPal",
        "url": "https://developer.paypal.com/"
    },
    "bugs": {
        "url": "https://github.com/paypal/PayPal-node-SDK/issues"
    },
    "config": {
        "blanket": {
            "pattern": "lib",
            "data-cover-never": "node_modules"
        }
    },
    "dependencies": {
        "buffer-crc32": "^0.2.3",
        "semver": "^5.0.3",
        "uuid": "^2.0.1"
    },
    "description": "SDK for PayPal REST APIs",
    "devDependencies": {
        "blanket": "~1.1.5",
        "chai": "~1.9.1",
        "coveralls": "~2.0.16",
        "grunt": "~0.4.1",
        "grunt-contrib-jshint": "~0.3.0",
        "grunt-jsdoc": "^0.5.8",
        "grunt-simple-mocha": "~0.4.0",
        "ink-docstrap": "^0.5.2",
        "jsdoc": "^3.3.0-beta1",
        "mocha": "~1.18.2",
        "mocha-lcov-reporter": "0.0.1",
        "nock": "0.36.2"
    },
    "directories": {},
    "dist": {
        "shasum": "1d73885cc775c38fb9b165d060a6c62138f400bd",
        "tarball": "https://registry.npmjs.org/paypal-rest-sdk/-/paypal-rest-sdk-1.7.1.tgz"
    },
    "engines": {
        "node": ">= v0.6.0"
    },
    "gitHead": "28c30c723268ac395ee06ceecf58013be6dbd5f3",
    "homepage": "https://github.com/paypal/PayPal-node-SDK",
    "keywords": [
        "paypal",
        "rest",
        "api",
        "sdk"
    ],
    "license": "SEE LICENSE IN https://github.com/paypal/PayPal-node-SDK/blob/master/LICENSE",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "paypal"
        }
    ],
    "man": [
        "README.md"
    ],
    "name": "paypal-rest-sdk",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/paypal/PayPal-node-SDK.git"
    },
    "scripts": {
        "test": "grunt"
    },
    "version": "1.7.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
