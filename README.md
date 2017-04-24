# npmtest-content-disposition

#### basic test coverage for  [content-disposition (v0.5.2)](https://github.com/jshttp/content-disposition#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-content-disposition.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-content-disposition) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-content-disposition.svg)](https://travis-ci.org/npmtest/node-npmtest-content-disposition)

#### Create and parse Content-Disposition header

[![NPM](https://nodei.co/npm/content-disposition.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/content-disposition)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-content-disposition/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-content-disposition/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-content-disposition/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-content-disposition/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-content-disposition/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-content-disposition/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-content-disposition/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-content-disposition/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-content-disposition/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-content-disposition/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-content-disposition/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-content-disposition/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-content-disposition/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-content-disposition/build/test-report.html](https://npmtest.github.io/node-npmtest-content-disposition/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-content-disposition/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-content-disposition/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-content-disposition/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-content-disposition/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-content-disposition/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-content-disposition/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-content-disposition/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-content-disposition/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/content-disposition/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        }
    ],
    "dependencies": {},
    "description": "Create and parse Content-Disposition header",
    "devDependencies": {
        "eslint": "3.11.1",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-promise": "3.3.0",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "0cf68bb9ddf5f2be7961c3a85178cb85dba78cb4",
        "tarball": "https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.2.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "2a08417377cf55678c9f870b305f3c6c088920f3",
    "homepage": "https://github.com/jshttp/content-disposition#readme",
    "keywords": [
        "content-disposition",
        "http",
        "rfc6266",
        "res"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "content-disposition",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/content-disposition.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "0.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
