# npmtest-gulp-group-concat

#### basic test coverage for  [gulp-group-concat (v1.1.5)](https://github.com/TakenPilot/gulp-group-concat)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-group-concat.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-group-concat) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-group-concat.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-group-concat)

#### Concats groups of files into a smaller number of files

[![NPM](https://nodei.co/npm/gulp-group-concat.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-group-concat)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-group-concat/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-group-concat/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-group-concat/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-group-concat/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-group-concat/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-group-concat/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dane Stuckel"
    },
    "bugs": {
        "url": "https://github.com/TakenPilot/gulp-group-concat/issues"
    },
    "config": {
        "blanket": {
            "pattern": "index.js",
            "data-cover-never": "node_modules"
        }
    },
    "dependencies": {
        "concat-with-sourcemaps": "^1.0.0",
        "globule": "^0.2.0",
        "gulp-util": "^3.0.3",
        "lodash": "^3.2.0",
        "through2": "^0.6.3",
        "vinyl-sourcemaps-apply": "^0.1.4"
    },
    "description": "Concats groups of files into a smaller number of files",
    "devDependencies": {
        "blanket": "^1.1.6",
        "chai": "^2.0.0",
        "coveralls": "^2.11.2",
        "gulp": "^3.8.11",
        "gulp-pleeease": "^1.1.0",
        "gulp-sourcemaps": "^1.3.0",
        "mocha": "^2.1.0",
        "mocha-lcov-reporter": "0.0.1",
        "sinon": "^1.12.2",
        "vinyl-buffer": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "80d53722e3f5951fbdc8df0b7bfe7412efb0b6ee",
        "tarball": "https://registry.npmjs.org/gulp-group-concat/-/gulp-group-concat-1.1.5.tgz"
    },
    "gitHead": "ab23e7fff4ed6bf11e1651ca9c02bb8047d675d1",
    "homepage": "https://github.com/TakenPilot/gulp-group-concat",
    "keywords": [
        "gulp",
        "gulpplugin",
        "gulpfriendly",
        "concat",
        "group",
        "filter",
        "sourcemaps",
        "multi",
        "pipe",
        "stream"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "danestuckel"
        }
    ],
    "name": "gulp-group-concat",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/TakenPilot/gulp-group-concat.git"
    },
    "scripts": {
        "test": "mocha -r blanket -R mocha-lcov-reporter | ./node_modules/coveralls/bin/coveralls.js"
    },
    "version": "1.1.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
