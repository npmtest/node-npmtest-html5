# npmtest-html5

#### basic test coverage for  html5 (vv1.0.5)  [![npm package](https://img.shields.io/npm/v/npmtest-html5.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html5) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html5.svg)](https://travis-ci.org/npmtest/node-npmtest-html5)

#### HTML5 HTML parser, including support for SVG and MathML foreign content

[![NPM](https://nodei.co/npm/html5.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html5)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html5/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html5/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html5/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html5/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html5/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html5/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html5/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html5/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html5/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html5/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html5/build/test-report.html](https://npmtest.github.io/node-npmtest-html5/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html5/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html5/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html5/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html5/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html5/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html5/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "html5",
    "description": "HTML5 HTML parser, including support for SVG and MathML foreign content",
    "version": "v1.0.5",
    "author": {
        "name": "Aria Stewart",
        "github": "aredridel",
        "url": "http://dinhe.net/~aredridel/"
    },
    "url": "http://dinhe.net/~aredridel/projects/js/html5/",
    "repository": {
        "type": "git",
        "url": "https://github.com/aredridel/html5"
    },
    "contributors": [
        {
            "name": "Arthur Taylor",
            "github": "codders"
        },
        {
            "name": "DanyaPostfactum",
            "github": "DanyaPostfactum"
        }
    ],
    "maintainers": [
        {
            "name": "Aria Stewart",
            "github": "aredridel",
            "url": "http://dinhe.net/~aredridel/"
        }
    ],
    "dependencies": {
        "opts": "^1.2.1",
        "html5-entities": "^1.0.0"
    },
    "optionalDependencies": {
        "jsdom": "^0.11.0"
    },
    "devDependencies": {
        "tape": "^1.0.4",
        "bench": "^0.3.3",
        "ronn": "^0.4.0"
    },
    "engines": {
        "npm": ">= 1.0",
        "node": ">= 0.8.0"
    },
    "main": "./lib/index.js",
    "directories": {
        "lib": "lib"
    },
    "scripts": {
        "test": "tape 'find test -name '*-test.js''"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
