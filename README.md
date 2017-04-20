# npmtest-immutability-helper

#### basic test coverage for  [immutability-helper (v2.1.2)](https://github.com/kolodny/immutability-helper#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-immutability-helper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-immutability-helper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-immutability-helper.svg)](https://travis-ci.org/npmtest/node-npmtest-immutability-helper)

#### mutate a copy of data without changing the original source

[![NPM](https://nodei.co/npm/immutability-helper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/immutability-helper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-immutability-helper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-immutability-helper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-immutability-helper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-immutability-helper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-immutability-helper/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-immutability-helper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-immutability-helper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-immutability-helper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-immutability-helper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-immutability-helper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-immutability-helper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-immutability-helper/build/test-report.html](https://npmtest.github.io/node-npmtest-immutability-helper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-immutability-helper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-immutability-helper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-immutability-helper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-immutability-helper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-immutability-helper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-immutability-helper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-immutability-helper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-immutability-helper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "immutability-helper",
    "version": "2.1.2",
    "description": "mutate a copy of data without changing the original source",
    "main": "index.js",
    "scripts": {
        "test-cov": "nyc npm test && nyc report --reporter=lcov",
        "test-travis": "nyc npm test && nyc report --reporter=lcov",
        "test": "mocha test.js"
    },
    "keywords": [
        "immutability"
    ],
    "author": "Moshe Kolodny",
    "license": "MIT",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "expect": "^1.14.0",
        "mocha": "^2.4.5",
        "nyc": "^5.6.0"
    },
    "dependencies": {
        "invariant": "^2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kolodny/immutability-helper.git"
    },
    "bugs": {
        "url": "https://github.com/kolodny/immutability-helper/issues"
    },
    "homepage": "https://github.com/kolodny/immutability-helper#readme"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
