# npmtest-wildcard

#### basic test coverage for  [wildcard (v1.1.2)](https://github.com/DamonOehlman/wildcard)  [![npm package](https://img.shields.io/npm/v/npmtest-wildcard.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wildcard) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wildcard.svg)](https://travis-ci.org/npmtest/node-npmtest-wildcard)

#### Wildcard matching tools

[![NPM](https://nodei.co/npm/wildcard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wildcard)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wildcard/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wildcard/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wildcard/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wildcard/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wildcard/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-wildcard/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-wildcard/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wildcard/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wildcard/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wildcard/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wildcard/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wildcard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wildcard/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wildcard/build/test-report.html](https://npmtest.github.io/node-npmtest-wildcard/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wildcard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wildcard/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wildcard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wildcard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wildcard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wildcard/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wildcard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wildcard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Damon Oehlman"
    },
    "bugs": {
        "url": "http://github.com/DamonOehlman/wildcard/issues"
    },
    "dependencies": {},
    "description": "Wildcard matching tools",
    "devDependencies": {
        "tape": "^3.0.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "a7020453084d8cd2efe70ba9d3696263de1710a5",
        "tarball": "https://registry.npmjs.org/wildcard/-/wildcard-1.1.2.tgz"
    },
    "gitHead": "d844aaa3ac09f35c79036178040c85b97ce74c54",
    "homepage": "https://github.com/DamonOehlman/wildcard",
    "keywords": [
        "string",
        "wildcard"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "damonoehlman"
        }
    ],
    "name": "wildcard",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/DamonOehlman/wildcard.git"
    },
    "scripts": {
        "gendocs": "gendocs > README.md",
        "test": "node test/all.js"
    },
    "testling": {
        "files": "test/all.js",
        "browsers": {
            "ie": [
                "latest"
            ],
            "ff": [
                "latest",
                "nightly"
            ],
            "chrome": [
                "latest",
                "canary"
            ],
            "opera": [
                "latest",
                "next"
            ],
            "safari": [
                "latest"
            ]
        }
    },
    "version": "1.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
