# npmtest-msgpack5

#### test coverage for  [msgpack5 (v3.4.1)](https://github.com/mcollina/msgpack5)  [![npm package](https://img.shields.io/npm/v/npmtest-msgpack5.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-msgpack5) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-msgpack5.svg)](https://travis-ci.org/npmtest/node-npmtest-msgpack5)

#### A msgpack v5 implementation for node.js and the browser, with extension points

[![NPM](https://nodei.co/npm/msgpack5.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/msgpack5)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-msgpack5/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-msgpack5/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-msgpack5/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-msgpack5/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-msgpack5/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-msgpack5/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-msgpack5/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-msgpack5/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-msgpack5/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-msgpack5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-msgpack5/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-msgpack5/build/test-report.html](https://npmtest.github.io/node-npmtest-msgpack5/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-msgpack5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-msgpack5/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-msgpack5/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-msgpack5/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-msgpack5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-msgpack5/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-msgpack5/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-msgpack5/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo collina"
    },
    "bugs": {
        "url": "https://github.com/mcollina/msgpack5/issues"
    },
    "dependencies": {
        "bl": "^1.0.0",
        "inherits": "^2.0.1",
        "readable-stream": "^2.0.1"
    },
    "description": "A msgpack v5 implementation for node.js and the browser, with extension points",
    "devDependencies": {
        "browserify": "^10.2.4",
        "faucet": "0.0.1",
        "jshint": "^2.5.2",
        "level-test": "^2.0.0",
        "pre-commit": "1.0.10",
        "standard": "^8.0.0",
        "tape": "^4.0.0",
        "testling": "^1.7.1",
        "uglify-js": "^2.4.15"
    },
    "directories": {},
    "dist": {
        "shasum": "350ef35899c6c8773710fd84d881ddd3340a8114",
        "tarball": "https://registry.npmjs.org/msgpack5/-/msgpack5-3.4.1.tgz"
    },
    "gitHead": "e56c0604bfff3e85a13e227c99b94962d3e1e005",
    "homepage": "https://github.com/mcollina/msgpack5",
    "keywords": [
        "msgpack",
        "extension",
        "v5",
        "msgpack",
        "v5",
        "ext"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "matteo.collina"
        }
    ],
    "name": "msgpack5",
    "optionalDependencies": {},
    "pre-commit": [
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/mcollina/msgpack5.git"
    },
    "scripts": {
        "browserify": "browserify index.js -o dist/msgpack5.js -s msgpack5",
        "build": "npm run browserify && npm run dist",
        "dist": "uglifyjs dist/msgpack5.js -o dist/msgpack5.min.js",
        "test": "standard && tape test/* | faucet",
        "test-browser": "browserify test/* | testling -u"
    },
    "standard": {
        "ignore": [
            "dist/"
        ]
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/6..latest",
            "chrome/22..latest",
            "firefox/16..latest",
            "safari/latest",
            "opera/11.0..latest",
            "iphone/6",
            "ipad/6",
            "android-browser/latest"
        ]
    },
    "version": "3.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
