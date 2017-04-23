# npmtest-express-ipfilter

#### basic test coverage for  [express-ipfilter (v0.2.4)](https://github.com/baminteractive/express-ipfilter#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-ipfilter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-ipfilter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-ipfilter.svg)](https://travis-ci.org/npmtest/node-npmtest-express-ipfilter)

#### A light-weight IP address based filtering system

[![NPM](https://nodei.co/npm/express-ipfilter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-ipfilter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-ipfilter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-ipfilter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-ipfilter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-ipfilter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-ipfilter/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-ipfilter/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-ipfilter/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-ipfilter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-ipfilter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-ipfilter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-ipfilter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-ipfilter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-ipfilter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-ipfilter/build/test-report.html](https://npmtest.github.io/node-npmtest-express-ipfilter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-ipfilter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-ipfilter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-ipfilter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-ipfilter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-ipfilter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-ipfilter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-ipfilter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-ipfilter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "BaM Interactive"
    },
    "bugs": {
        "url": "https://github.com/baminteractive/express-ipfilter/issues"
    },
    "dependencies": {
        "ip": "~1.1.0",
        "lodash": "~3.10.1",
        "range_check": "^1.2.0"
    },
    "description": "A light-weight IP address based filtering system",
    "devDependencies": {
        "babel-preset-es2015": "^6.6.0",
        "grunt": "^0.4.5",
        "grunt-babel": "^6.0.0",
        "grunt-check-dependencies": "^0.12.0",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-copy": "^0.8.2",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-eslint": "^19.0.0",
        "grunt-mocha-istanbul": "^3.0.1",
        "grunt-mocha-test": "~0.12.7",
        "istanbul": "^0.4.0",
        "load-grunt-tasks": "^3.3.0",
        "minimatch": "^3.0.3",
        "mocha": "^2.5.3",
        "mocha-junit-reporter": "^1.9.1",
        "publish": "^0.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "959a8c08ed24f7c1f1a0b7746a5b2fafe0d5c8b7",
        "tarball": "https://registry.npmjs.org/express-ipfilter/-/express-ipfilter-0.2.4.tgz"
    },
    "homepage": "https://github.com/baminteractive/express-ipfilter#readme",
    "keywords": [
        "middleware",
        "ipfilter",
        "ip filter",
        "ipban",
        "ip ban",
        "express"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ryanbillingsley"
        }
    ],
    "name": "express-ipfilter",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/baminteractive/express-ipfilter.git"
    },
    "scripts": {
        "push": "publish",
        "test": "mocha -R spec"
    },
    "version": "0.2.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
