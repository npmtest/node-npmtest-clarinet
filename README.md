# npmtest-clarinet

#### test coverage for  [clarinet (v0.11.0)](https://github.com/dscape/clarinet)  [![npm package](https://img.shields.io/npm/v/npmtest-clarinet.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-clarinet) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-clarinet.svg)](https://travis-ci.org/npmtest/node-npmtest-clarinet)

#### SAX based evented streaming JSON parser in JavaScript (browser and node)

[![NPM](https://nodei.co/npm/clarinet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/clarinet)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-clarinet/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-clarinet/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-clarinet/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-clarinet/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-clarinet/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-clarinet/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-clarinet/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-clarinet/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-clarinet/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-clarinet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-clarinet/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-clarinet/build/test-report.html](https://npmtest.github.io/node-npmtest-clarinet/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-clarinet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-clarinet/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-clarinet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-clarinet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clarinet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clarinet/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-clarinet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-clarinet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nuno Job",
        "url": "http://nunojob.com/"
    },
    "bugs": {
        "url": "http://github.com/dscape/clarinet/issues"
    },
    "contributors": [
        {
            "name": "Jann Horn",
            "url": "https://github.com/thejh"
        },
        {
            "name": "Justin Makeig",
            "url": "http://www.audiblepop.com"
        },
        {
            "name": "Roly Fentanes",
            "url": "http://about.me/roly"
        },
        {
            "name": "John Lancaster",
            "url": "http://jlank.com"
        }
    ],
    "dependencies": {},
    "description": "SAX based evented streaming JSON parser in JavaScript (browser and node)",
    "devDependencies": {
        "mocha": "1.3.x",
        "should": "1.0.x",
        "underscore": "1.2.3"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "6cc912b93138dc867fc273cd34ea90e83e054719",
        "tarball": "https://registry.npmjs.org/clarinet/-/clarinet-0.11.0.tgz"
    },
    "engines": {
        "chrome": ">=16.0.912",
        "firefox": ">=0.8.0",
        "node": ">=0.3.6"
    },
    "homepage": "https://github.com/dscape/clarinet",
    "keywords": [
        "sax",
        "json",
        "parser",
        "stream",
        "streaming",
        "event",
        "events",
        "emitter",
        "async",
        "streamer",
        "browser"
    ],
    "license": "BSD",
    "main": "./clarinet.js",
    "maintainers": [
        {
            "name": "dscape"
        },
        {
            "name": "thejh"
        }
    ],
    "name": "clarinet",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/dscape/clarinet.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha -r should -t 10000 -s 2000  test/clarinet.js test/npm.js test/utf8-chunks.js test/position.js"
    },
    "version": "0.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
