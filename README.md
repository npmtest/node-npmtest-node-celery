# npmtest-node-celery

#### basic test coverage for  node-celery (v0.2.8)  [![npm package](https://img.shields.io/npm/v/npmtest-node-celery.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-celery) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-celery.svg)](https://travis-ci.org/npmtest/node-npmtest-node-celery)

#### Celery client for Node

[![NPM](https://nodei.co/npm/node-celery.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-celery)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-celery/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-celery/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-celery/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-celery/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-celery/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-celery/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-celery/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-celery/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-celery/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-celery/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-celery/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-celery/build/test-report.html](https://npmtest.github.io/node-npmtest-node-celery/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-celery/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-celery/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-celery/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-celery/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-celery/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-celery/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-celery/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-celery/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-celery",
    "version": "0.2.8",
    "description": "Celery client for Node",
    "author": "Mher Movsisyan <mher.movsisyan@gmail.com>",
    "scripts": {
        "test": "mocha tests"
    },
    "dependencies": {
        "amqp": "*",
        "node-uuid": "*",
        "redis": "*"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/mher/node-celery.git"
    },
    "devDependencies": {
        "mocha": "*"
    },
    "engine": "node >= 0.8.2",
    "main": "celery.js"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
