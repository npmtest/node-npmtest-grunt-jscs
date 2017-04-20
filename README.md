# npmtest-grunt-jscs

#### basic test coverage for  [grunt-jscs (v3.0.1)](https://github.com/jscs-dev/grunt-jscs)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-jscs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-jscs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-jscs.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-jscs)

#### Grunt task for checking JavaScript Code Style with jscs.

[![NPM](https://nodei.co/npm/grunt-jscs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-jscs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-jscs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-jscs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-jscs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-jscs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-jscs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-jscs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-jscs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-jscs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-jscs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-jscs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-jscs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-jscs/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-jscs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-jscs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-jscs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-jscs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-jscs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-jscs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gustavo Henke"
    },
    "bugs": {
        "url": "https://github.com/jscs-dev/grunt-jscs/issues"
    },
    "dependencies": {
        "hooker": "~0.2.3",
        "jscs": "~3.0.5",
        "lodash": "~4.6.1",
        "vow": "~0.4.1"
    },
    "description": "Grunt task for checking JavaScript Code Style with jscs.",
    "devDependencies": {
        "grunt": "1.0.1",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-nodeunit": "~1.0.0",
        "load-grunt-tasks": "^3.4.0",
        "time-grunt": "~1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1fae50e3e955df9e3a9d9425aec22accae008092",
        "tarball": "https://registry.npmjs.org/grunt-jscs/-/grunt-jscs-3.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "tasks",
        "LICENSE-MIT"
    ],
    "gitHead": "efff3087a86296b4a6e8810a0f5e4c215be6210d",
    "homepage": "https://github.com/jscs-dev/grunt-jscs",
    "keywords": [
        "gruntplugin",
        "jscs",
        "code style",
        "checker"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "gustavohenke"
        },
        {
            "name": "markelog"
        }
    ],
    "name": "grunt-jscs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jscs-dev/grunt-jscs.git"
    },
    "scripts": {
        "bump": "npm version patch -m \"Release v%s\"",
        "bump-major": "npm version major -m \"Release v%s\"",
        "bump-minor": "npm version minor -m \"Release v%s\"",
        "test": "grunt test"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
