# npmtest-office

#### basic test coverage for  [office (v0.0.8)](https://github.com/dkiyatkin/node-office)  [![npm package](https://img.shields.io/npm/v/npmtest-office.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-office) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-office.svg)](https://travis-ci.org/npmtest/node-npmtest-office)

#### Parse office documents (doc, docx, xls, etc..)

[![NPM](https://nodei.co/npm/office.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/office)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-office/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-office/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-office/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-office/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-office/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-office/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-office/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-office/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-office/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-office/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-office/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-office/build/test-report.html](https://npmtest.github.io/node-npmtest-office/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-office/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-office/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-office/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-office/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-office/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-office/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-office/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-office/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "office",
    "version": "0.0.8",
    "description": "Parse office documents (doc, docx, xls, etc..)",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "scripts": {
        "test": "grunt nodeunit"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/dkiyatkin/node-office.git"
    },
    "keywords": [
        "doc",
        "xls",
        "docx",
        "xlsx",
        "odt",
        "ods"
    ],
    "author": "Dmitriy Kiyatkin <info@dkiyatkin.com> (http://dkiyatkin.com/)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/dkiyatkin/node-office/issues"
    },
    "homepage": "https://github.com/dkiyatkin/node-office",
    "devDependencies": {
        "grunt": "~0.4.2",
        "grunt-contrib-jshint": "~0.8.0",
        "grunt-contrib-nodeunit": "~0.2.2",
        "htmlparser": "~1.7.7"
    },
    "dependencies": {
        "xml2json": "~0.3.2",
        "temp": "~0.6.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
