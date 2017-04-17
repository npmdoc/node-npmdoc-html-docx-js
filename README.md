# api documentation for  [html-docx-js (v0.3.1)](https://github.com/evidenceprime/html-docx-js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-html-docx-js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-html-docx-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-html-docx-js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-html-docx-js)
#### Converts HTML documents to DOCX in the browser

[![NPM](https://nodei.co/npm/html-docx-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html-docx-js)

- [https://npmdoc.github.io/node-npmdoc-html-docx-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html-docx-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-docx-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-docx-js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-html-docx-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-html-docx-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Artur Nowak"
    },
    "browserify": {
        "transform": [
            "coffeeify",
            "brfs"
        ]
    },
    "bugs": {
        "url": "https://github.com/evidenceprime/html-docx-js/issues"
    },
    "contributors": [
        {
            "name": "Ievgen Martynov"
        }
    ],
    "dependencies": {
        "jszip": "^2.3.0",
        "lodash.escape": "^3.0.0",
        "lodash.merge": "^3.2.0"
    },
    "description": "Converts HTML documents to DOCX in the browser",
    "devDependencies": {
        "brfs": "^1.1.2",
        "browserify": "^4.2.0",
        "chai": "^1.9.1",
        "coffeeify": "^0.6.0",
        "del": "^1.2.0",
        "gulp": "^3.8.5",
        "gulp-coffee": "^2.3.1",
        "gulp-lodash-template": "^0.1.0",
        "gulp-mocha": "^0.4.1",
        "gulp-mocha-phantomjs": "^0.3.0",
        "gulp-notify": "^1.4.0",
        "gulp-util": "^2.2.19",
        "jstify": "^0.9.0",
        "mocha": "^1.20.1",
        "pretty-hrtime": "^0.2.1",
        "sinon": "^1.10.2",
        "sinon-chai": "^2.5.0",
        "vinyl-source-stream": "^0.1.1",
        "watchify": "^0.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "9713f6587a08d1f0c87a801fe7649a4d0ab07d76",
        "tarball": "https://registry.npmjs.org/html-docx-js/-/html-docx-js-0.3.1.tgz"
    },
    "gitHead": "68f2235b2948419f1407e9b7788973715acf5d08",
    "homepage": "https://github.com/evidenceprime/html-docx-js#readme",
    "license": "MIT",
    "main": "build/api.js",
    "maintainers": [
        {
            "name": "anowak"
        }
    ],
    "name": "html-docx-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/evidenceprime/html-docx-js.git"
    },
    "scripts": {
        "prepublish": "gulp clean; gulp build-node",
        "test": "gulp test-node"
    },
    "version": "0.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
