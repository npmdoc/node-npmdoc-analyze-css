# npmdoc-analyze-css

#### api documentation for  [analyze-css (v0.12.4)](https://github.com/macbre/analyze-css#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-analyze-css.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-analyze-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-analyze-css.svg)](https://travis-ci.org/npmdoc/node-npmdoc-analyze-css)

#### CSS selectors complexity and performance analyzer

[![NPM](https://nodei.co/npm/analyze-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/analyze-css)

- [https://npmdoc.github.io/node-npmdoc-analyze-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-analyze-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-analyze-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-analyze-css/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-analyze-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-analyze-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maciej Brencz",
        "url": "https://github.com/macbre"
    },
    "bin": {
        "analyze-css": "./bin/analyze-css.js"
    },
    "bugs": {
        "url": "https://github.com/macbre/analyze-css/issues"
    },
    "dependencies": {
        "cli": "^1.0.0",
        "css": "2.2.x",
        "css-shorthand-properties": "1.0.x",
        "debug": "2.2.x",
        "fast-stats": "0.0.x",
        "glob": "^7.0.6",
        "http-proxy-agent": "^1.0.0",
        "node-fetch": "^1.6.1",
        "onecolor": "^3.0.4",
        "optimist": "0.6.x",
        "slick": "~1.12.1",
        "specificity": "^0.2.1"
    },
    "description": "CSS selectors complexity and performance analyzer",
    "devDependencies": {
        "autoprefixer-core": "^6.0.1",
        "browserslist": "^1.3.6",
        "istanbul": "^0.4.5",
        "js-beautify": "^1.6.4",
        "jshint": "^2.9.3",
        "mocha": "^3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "bd5052150f68d14c48fd41e0efeee2a35209551e",
        "tarball": "https://registry.npmjs.org/analyze-css/-/analyze-css-0.12.4.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "1d805757990c22089d4b17dc70c87228a195c761",
    "homepage": "https://github.com/macbre/analyze-css#readme",
    "jshintConfig": {
        "node": true,
        "strict": true,
        "validthis": true
    },
    "keywords": [
        "analysis",
        "complexity",
        "css",
        "stylesheet",
        "webperf"
    ],
    "license": "BSD-2-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "macbre"
        }
    ],
    "name": "analyze-css",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/macbre/analyze-css.git"
    },
    "scripts": {
        "beautify": "js-beautify -r rules/*.js test/*.js test/rules/*.js bin/*.js lib/*.js lib/preprocessors/*.js",
        "coverage": "istanbul cover  _mocha -- -R spec",
        "lint": "jshint --verbose bin/ lib/ rules/ test/",
        "prefixes": "DEBUG=* node data/prefixes.js",
        "test": "mocha -R spec"
    },
    "version": "0.12.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
