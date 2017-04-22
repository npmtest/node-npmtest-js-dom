# npmtest-js-dom

#### basic test coverage for  [js-dom (v0.0.1)](https://github.com/tmpvar/jsdom)  [![npm package](https://img.shields.io/npm/v/npmtest-js-dom.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-js-dom) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-js-dom.svg)](https://travis-ci.org/npmtest/node-npmtest-js-dom)

#### A JavaScript implementation of the DOM and HTML standards

[![NPM](https://nodei.co/npm/js-dom.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/js-dom)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-js-dom/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-js-dom/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-js-dom/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-js-dom/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-js-dom/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-js-dom/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-js-dom/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-js-dom/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-js-dom/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-js-dom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-js-dom/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-js-dom/build/test-report.html](https://npmtest.github.io/node-npmtest-js-dom/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-js-dom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-js-dom/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-js-dom/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-js-dom/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-js-dom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-js-dom/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-js-dom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-js-dom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "http://github.com/tmpvar/jsdom/issues"
    },
    "contributors": [
        {
            "name": "Vincent Greene"
        },
        {
            "name": "Dav Glass"
        },
        {
            "name": "Felix Gnass"
        },
        {
            "name": "Charlie Robbins"
        },
        {
            "name": "Aria Stewart"
        },
        {
            "name": "Matthew",
            "url": "http://github.com/matthewpflueger/"
        },
        {
            "name": "Olivier El Mekki",
            "url": "http://blog.olivier-elmekki.com/"
        },
        {
            "name": "Shimon Dookdin"
        },
        {
            "name": "Daniel Cassidy",
            "url": "http://www.danielcassidy.me.uk/"
        },
        {
            "name": "Sam Ruby",
            "url": "http://intertwingly.net/blog/"
        },
        {
            "name": "hij1nx",
            "url": "http://github.com/hij1nx"
        },
        {
            "name": "Yonathan Randolph",
            "url": "http://github.com/yonran"
        },
        {
            "name": "Martin Davis",
            "url": "http://github.com/waslogic"
        },
        {
            "name": "Andreas Lind Petersen"
        },
        {
            "name": "d-ash",
            "url": "http://github.com/d-ash"
        },
        {
            "name": "Robin Zhong"
        },
        {
            "name": "Alexander Flatter"
        },
        {
            "name": "Heng Liu"
        },
        {
            "name": "Brian McDaniel",
            "url": "http://github.com/brianmcd"
        },
        {
            "name": "John Hurliman"
        },
        {
            "name": "Jimmy Mabey"
        },
        {
            "name": "Gregory Tomlinson"
        },
        {
            "name": "Jason Davies",
            "url": "http://www.jasondavies.com/"
        },
        {
            "name": "Josh Marshall",
            "url": "http://www.ponderingtheobvious.com/"
        },
        {
            "name": "Jason Priestley",
            "url": "https://github.com/jhp"
        },
        {
            "name": "Derek Lindahl",
            "url": "https://github.com/dlindahl"
        },
        {
            "name": "Chris Roebuck",
            "url": "http://www.quillu.com"
        },
        {
            "name": "Avi Deitcher",
            "url": "https://github.com/deitch"
        },
        {
            "name": "Nao Iizuka",
            "url": "https://github.com/iizukanao"
        },
        {
            "name": "Peter Perenyi",
            "url": "https://github.com/sinegar"
        },
        {
            "name": "Tiago Rodrigues",
            "url": "http://trodrigues.net"
        },
        {
            "name": "Samori Gorse",
            "url": "http://github.com/shinuza"
        },
        {
            "name": "John Roberts"
        },
        {
            "name": "Chad Walker",
            "url": "https://github.com/chad3814"
        },
        {
            "name": "Zach Smith",
            "url": "https://github.com/xcoderzach"
        }
    ],
    "dependencies": {
        "contextify": "~0.1.5",
        "cssom": "~0.3.0",
        "cssstyle": "~0.2.9",
        "htmlparser2": ">= 3.1.5 <4",
        "iconv-lite": "0.4.4",
        "nwmatcher": "~1.3.2",
        "parse5": "~1.0.0",
        "request": "2.x",
        "xmlhttprequest": ">=1.5.0"
    },
    "description": "A JavaScript implementation of the DOM and HTML standards",
    "devDependencies": {
        "nodeunit": "~0.8.0",
        "optimist": "*",
        "urlmaster": ">=0.2.15"
    },
    "directories": {},
    "dist": {
        "shasum": "5880ac5febc33a73a63a17e116625431312a3834",
        "tarball": "https://registry.npmjs.org/js-dom/-/js-dom-0.0.1.tgz"
    },
    "homepage": "https://github.com/tmpvar/jsdom",
    "keywords": [
        "dom",
        "html",
        "whatwg",
        "w3c"
    ],
    "license": {
        "type": "MIT",
        "url": "http://github.com/tmpvar/jsdom/blob/master/LICENSE.txt"
    },
    "main": "./lib/jsdom",
    "maintainers": [
        {
            "name": "seon"
        }
    ],
    "name": "js-dom",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tmpvar/jsdom.git"
    },
    "scripts": {
        "test": "node ./test/runner"
    },
    "version": "0.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
