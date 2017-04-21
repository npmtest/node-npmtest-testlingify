# npmtest-testlingify

#### basic test coverage for  [testlingify (v0.3.0)](https://github.com/thlorenz/testlingify)  [![npm package](https://img.shields.io/npm/v/npmtest-testlingify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-testlingify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-testlingify.svg)](https://travis-ci.org/npmtest/node-npmtest-testlingify)

#### Adds github hooks and browser config for testling.

[![NPM](https://nodei.co/npm/testlingify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/testlingify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-testlingify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-testlingify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-testlingify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-testlingify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-testlingify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-testlingify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-testlingify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-testlingify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-testlingify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-testlingify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-testlingify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-testlingify/build/test-report.html](https://npmtest.github.io/node-npmtest-testlingify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-testlingify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-testlingify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-testlingify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-testlingify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-testlingify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-testlingify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-testlingify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-testlingify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "testlingify",
    "version": "0.3.0",
    "description": "Adds github hooks and browser config for testling.",
    "bin": "bin/testlingify.js",
    "scripts": {
        "test": "tap test/*.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/testlingify.git"
    },
    "homepage": "https://github.com/thlorenz/testlingify",
    "dependencies": {
        "request": "~2.21.0",
        "resolve-git-remote": "~0.1.0",
        "find-parent-dir": "~0.1.0",
        "mkdirp": "~0.3.5",
        "npmlog": "0.0.2",
        "configurate": "~0.1.4",
        "promfig": "~0.1.1",
        "json-file-plus": "~0.2.0"
    },
    "devDependencies": {
        "tap": "~0.4.3"
    },
    "keywords": [
        "testling",
        "browserify",
        "hook",
        "github",
        "ci",
        "travisci",
        "travis",
        "browserling"
    ],
    "author": {
        "name": "Thorsten Lorenz",
        "url": "http://thlorenz.com"
    },
    "license": "MIT",
    "engine": {
        "node": ">=0.6"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
