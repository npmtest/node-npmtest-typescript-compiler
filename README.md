# npmtest-typescript-compiler

#### basic test coverage for  [typescript-compiler (v1.4.1-2)](https://github.com/theblacksmith/typescript-compiler)  [![npm package](https://img.shields.io/npm/v/npmtest-typescript-compiler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-typescript-compiler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-typescript-compiler.svg)](https://travis-ci.org/npmtest/node-npmtest-typescript-compiler)

#### Typescript compiler wrapper

[![NPM](https://nodei.co/npm/typescript-compiler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/typescript-compiler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-typescript-compiler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-typescript-compiler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-typescript-compiler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-typescript-compiler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-typescript-compiler/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-typescript-compiler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-typescript-compiler/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-typescript-compiler/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-typescript-compiler/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-typescript-compiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-typescript-compiler/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-typescript-compiler/build/test-report.html](https://npmtest.github.io/node-npmtest-typescript-compiler/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-typescript-compiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-typescript-compiler/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-typescript-compiler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-typescript-compiler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-typescript-compiler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-typescript-compiler/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-typescript-compiler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-typescript-compiler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "typescript-compiler",
    "version": "1.4.1-2",
    "description": "Typescript compiler wrapper",
    "main": "index.js",
    "scripts": {
        "build": "make build",
        "test": "make build && mocha --compilers ts:typescript-require"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/theblacksmith/typescript-compiler.git"
    },
    "keywords": [
        "TypeScript",
        "compiler",
        "language",
        "javascript",
        "api"
    ],
    "author": "The Blacksmith (a.k.a. Saulo Vallory)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/theblacksmith/typescript-compiler/issues"
    },
    "homepage": "https://github.com/theblacksmith/typescript-compiler",
    "readmeFilename": "README.md",
    "devDependencies": {
        "chai": "^1.10.0",
        "mocha": "^2.0.1",
        "typescript-require": ">=0.2.7"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
