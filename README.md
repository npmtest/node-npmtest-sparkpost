# npmtest-sparkpost

#### basic test coverage for  [sparkpost (v2.1.2)](https://github.com/SparkPost/node-sparkpost)  [![npm package](https://img.shields.io/npm/v/npmtest-sparkpost.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sparkpost) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sparkpost.svg)](https://travis-ci.org/npmtest/node-npmtest-sparkpost)

#### A Node.js wrapper for interfacing with your favorite SparkPost APIs

[![NPM](https://nodei.co/npm/sparkpost.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sparkpost)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sparkpost/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sparkpost/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sparkpost/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sparkpost/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sparkpost/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sparkpost/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sparkpost/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sparkpost/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sparkpost/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sparkpost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sparkpost/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sparkpost/build/test-report.html](https://npmtest.github.io/node-npmtest-sparkpost/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sparkpost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sparkpost/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sparkpost/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sparkpost/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sparkpost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sparkpost/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sparkpost/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sparkpost/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sparkpost",
    "version": "2.1.2",
    "description": "A Node.js wrapper for interfacing with your favorite SparkPost APIs",
    "main": "./lib/sparkpost.js",
    "scripts": {
        "coveralls": "cat ./test/reports/lcov.info | coveralls",
        "pretest": "eslint lib/**",
        "test": "istanbul cover --report lcov --dir test/reports/ _mocha --recursive ./test/spec --grep ./test/**/*.spec.js -- --colors --reporter spec",
        "postversion": "git push upstream && git push --tags upstream"
    },
    "keywords": [
        "email",
        "messaging"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/SparkPost/node-sparkpost"
    },
    "author": "Message Systems, Inc.",
    "license": "Apache-2.0",
    "bugs": {
        "url": "https://github.com/SparkPost/node-sparkpost/issues"
    },
    "homepage": "https://github.com/SparkPost/node-sparkpost",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "coveralls": "^2.11.15",
        "eslint": "^3.12.2",
        "eslint-config-sparkpost": "^1.3.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "nock": "^9.0.0",
        "sinon": "^1.17.5",
        "sinon-as-promised": "^4.0.2",
        "sinon-chai": "^2.8.0"
    },
    "dependencies": {
        "lodash": "^4.17.2",
        "request": "^2.79.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
