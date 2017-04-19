# npmtest-zeroclipboard

#### test coverage for  [zeroclipboard (v2.3.0)](http://zeroclipboard.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-zeroclipboard.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-zeroclipboard) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-zeroclipboard.svg)](https://travis-ci.org/npmtest/node-npmtest-zeroclipboard)

#### The ZeroClipboard library provides an easy way to copy text to the clipboard using an invisible Adobe Flash movie and a JavaScript interface

[![NPM](https://nodei.co/npm/zeroclipboard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/zeroclipboard)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-zeroclipboard/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-zeroclipboard/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-zeroclipboard/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-zeroclipboard/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-zeroclipboard/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-zeroclipboard/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-zeroclipboard/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-zeroclipboard/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-zeroclipboard/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-zeroclipboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-zeroclipboard/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-zeroclipboard/build/test-report.html](https://npmtest.github.io/node-npmtest-zeroclipboard/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-zeroclipboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-zeroclipboard/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-zeroclipboard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-zeroclipboard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zeroclipboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zeroclipboard/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-zeroclipboard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-zeroclipboard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/zeroclipboard/zeroclipboard/issues"
    },
    "contributors": [
        {
            "name": "Jon Rohan",
            "url": "http://jonrohan.me/"
        },
        {
            "name": "James M. Greene",
            "url": "http://greene.io/"
        }
    ],
    "dependencies": {},
    "description": "The ZeroClipboard library provides an easy way to copy text to the clipboard using an invisible Adobe Flash movie and a JavaScript interface",
    "devDependencies": {
        "flex-sdk": "~4.6.0-0",
        "flexpmd": "^1.3.0-1",
        "grunt": "^0.4.5",
        "grunt-chmod": "^1.0.3",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-concat": "^0.5.1",
        "grunt-contrib-connect": "^0.11.2",
        "grunt-contrib-jshint": "^0.11.2",
        "grunt-contrib-uglify": "^0.9.2",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-coveralls": "^1.0.0",
        "grunt-flexpmd": "^0.1.3",
        "grunt-json-format": "^1.0.1",
        "grunt-mxmlc": "^0.5.2",
        "grunt-qunit-istanbul": "^0.5.0",
        "grunt-template": "^0.2.3",
        "jquery": "^2.1.4",
        "load-grunt-tasks": "^3.2.0",
        "qunit-composite": "^1.1.0",
        "qunitjs": "^1.18.0",
        "spm": "^3.6.11"
    },
    "directories": {},
    "dist": {
        "shasum": "592ebd833a4308688b0739697d3dbf989002c9af",
        "tarball": "https://registry.npmjs.org/zeroclipboard/-/zeroclipboard-2.3.0.tgz"
    },
    "files": [
        "dist/ZeroClipboard.*",
        "package.json",
        "LICENSE"
    ],
    "gitHead": "9ddfc4623bda247f3647733f7ca3bed5bd5e4972",
    "homepage": "http://zeroclipboard.org/",
    "keywords": [
        "flash",
        "clipboard",
        "copy",
        "cut",
        "paste",
        "zclip",
        "clip",
        "clippy"
    ],
    "license": "MIT",
    "main": "dist/ZeroClipboard.js",
    "maintainers": [
        {
            "name": "jonrohan"
        },
        {
            "name": "jamesmgreene"
        }
    ],
    "name": "zeroclipboard",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeroclipboard/zeroclipboard.git"
    },
    "scripts": {
        "postpublish": "spm publish",
        "test": "grunt travis --verbose"
    },
    "spm": {
        "main": "dist/ZeroClipboard.js",
        "output": [
            "dist/ZeroClipboard.swf",
            "dist/ZeroClipboard.Core.js"
        ]
    },
    "title": "ZeroClipboard",
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
