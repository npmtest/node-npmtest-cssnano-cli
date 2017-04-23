# npmtest-cssnano-cli

#### basic test coverage for  [cssnano-cli (v1.0.5)](https://github.com/ben-eb/cssnano-cli)  [![npm package](https://img.shields.io/npm/v/npmtest-cssnano-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cssnano-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cssnano-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-cssnano-cli)

#### A CLI for modular minifier cssnano.

[![NPM](https://nodei.co/npm/cssnano-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cssnano-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cssnano-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cssnano-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cssnano-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cssnano-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cssnano-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cssnano-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cssnano-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cssnano-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cssnano-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cssnano-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cssnano-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cssnano-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cssnano-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cssnano-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-cssnano-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cssnano-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cssnano-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cssnano-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cssnano-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cssnano-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cssnano-cli",
    "version": "1.0.5",
    "description": "A CLI for modular minifier cssnano.",
    "bin": {
        "cssnano": "cmd.js"
    },
    "files": [
        "cmd.js",
        "usage.txt",
        "LICENSE-MIT"
    ],
    "scripts": {
        "test": "tape test.js | tap-spec"
    },
    "keywords": [
        "cli",
        "cli-app",
        "cssnano",
        "compress",
        "minify",
        "optimise",
        "optimisation",
        "postcss"
    ],
    "license": "MIT",
    "dependencies": {
        "cssnano": "^3.0.0",
        "minimist": "^1.2.0",
        "read-file-stdin": "^0.2.0",
        "write-file-stdout": "0.0.2"
    },
    "devDependencies": {
        "tap-spec": "^4.1.0",
        "tape": "^4.2.0"
    },
    "homepage": "https://github.com/ben-eb/cssnano-cli",
    "author": {
        "name": "Ben Briggs",
        "url": "http://beneb.info"
    },
    "repository": "ben-eb/cssnano-cli"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
