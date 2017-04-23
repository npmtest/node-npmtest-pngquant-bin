# npmtest-pngquant-bin

#### basic test coverage for  [pngquant-bin (v3.1.1)](https://github.com/imagemin/pngquant-bin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pngquant-bin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pngquant-bin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pngquant-bin.svg)](https://travis-ci.org/npmtest/node-npmtest-pngquant-bin)

#### pngquant wrapper that makes it seamlessly available as a local dependency

[![NPM](https://nodei.co/npm/pngquant-bin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pngquant-bin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pngquant-bin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pngquant-bin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pngquant-bin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pngquant-bin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pngquant-bin/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-pngquant-bin/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-pngquant-bin/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pngquant-bin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pngquant-bin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pngquant-bin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pngquant-bin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pngquant-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pngquant-bin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pngquant-bin/build/test-report.html](https://npmtest.github.io/node-npmtest-pngquant-bin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pngquant-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pngquant-bin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pngquant-bin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pngquant-bin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pngquant-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pngquant-bin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pngquant-bin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pngquant-bin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin Mårtensson",
        "url": "github.com/kevva"
    },
    "bin": {
        "pngquant": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/imagemin/pngquant-bin/issues"
    },
    "dependencies": {
        "bin-build": "^2.0.0",
        "bin-wrapper": "^3.0.0",
        "logalot": "^2.0.0"
    },
    "description": "pngquant wrapper that makes it seamlessly available as a local dependency",
    "devDependencies": {
        "bin-check": "^2.0.0",
        "compare-size": "^1.0.0",
        "mkdirp": "^0.5.0",
        "mocha": "^2.2.4",
        "rimraf": "^2.3.2",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "d124d98a75a9487f40c1640b4dbfcbb2bd5a1fd1",
        "tarball": "https://registry.npmjs.org/pngquant-bin/-/pngquant-bin-3.1.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "cli.js",
        "index.js",
        "lib"
    ],
    "gitHead": "cec8114133e080cf836252b8a98f0c3083dcc0e4",
    "homepage": "https://github.com/imagemin/pngquant-bin#readme",
    "keywords": [
        "compress",
        "image",
        "img",
        "minify",
        "optimize",
        "png"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kevva"
        },
        {
            "name": "shinnn"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "pngquant-bin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/imagemin/pngquant-bin.git"
    },
    "scripts": {
        "postinstall": "node lib/install.js",
        "test": "xo && mocha"
    },
    "version": "3.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
