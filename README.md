# test coverage for  [forever-monitor (v1.7.1)](https://github.com/nodejitsu/forever-monitor#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-forever-monitor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-forever-monitor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-forever-monitor.svg)](https://travis-ci.org/npmtest/node-npmtest-forever-monitor)
#### Core forever process monitor

[![NPM](https://nodei.co/npm/forever-monitor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/forever-monitor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-forever-monitor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-forever-monitor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-forever-monitor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-forever-monitor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-forever-monitor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-forever-monitor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-forever-monitor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-forever-monitor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-forever-monitor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-forever-monitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-forever-monitor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-forever-monitor/build/test-report.html](https://npmtest.github.io/node-npmtest-forever-monitor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-forever-monitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-forever-monitor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-forever-monitor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-forever-monitor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-forever-monitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-forever-monitor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-forever-monitor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-forever-monitor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bugs": {
        "url": "https://github.com/nodejitsu/forever-monitor/issues"
    },
    "contributors": [
        {
            "name": "Charlie Robbins"
        },
        {
            "name": "Fedor Indutny"
        },
        {
            "name": "James Halliday"
        },
        {
            "name": "Bradley Meck"
        },
        {
            "name": "Dominic Tarr"
        },
        {
            "name": "Maciej Małecki"
        }
    ],
    "dependencies": {
        "broadway": "~0.3.6",
        "chokidar": "^1.0.1",
        "minimatch": "~3.0.2",
        "ps-tree": "0.0.x",
        "utile": "~0.2.1"
    },
    "description": "Core forever process monitor",
    "devDependencies": {
        "optimist": "~0.6.1",
        "vows": "~0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5d820f4a3a78db2d81ae2671f158b9e86a091bb8",
        "tarball": "https://registry.npmjs.org/forever-monitor/-/forever-monitor-1.7.1.tgz"
    },
    "engines": {
        "node": ">= 0.8.x"
    },
    "gitHead": "7d1c4631d831a017b7ae9430585f8b7324f66162",
    "homepage": "https://github.com/nodejitsu/forever-monitor#readme",
    "keywords": [
        "fault tolerant",
        "sysadmin",
        "tools"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "jcrugzz"
        }
    ],
    "name": "forever-monitor",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nodejitsu/forever-monitor.git"
    },
    "scripts": {
        "test": "vows test/**/*-test.js --spec -i"
    },
    "version": "1.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
