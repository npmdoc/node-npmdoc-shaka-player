# npmdoc-shaka-player

#### api documentation for  [shaka-player (v2.0.8)](https://github.com/google/shaka-player)  [![npm package](https://img.shields.io/npm/v/npmdoc-shaka-player.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-shaka-player) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-shaka-player.svg)](https://travis-ci.org/npmdoc/node-npmdoc-shaka-player)

#### DASH/EME video player library

[![NPM](https://nodei.co/npm/shaka-player.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shaka-player)

- [https://npmdoc.github.io/node-npmdoc-shaka-player/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shaka-player/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shaka-player/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shaka-player/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-shaka-player/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-shaka-player/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "shaka-player",
    "description": "DASH/EME video player library",
    "version": "2.0.8",
    "homepage": "https://github.com/google/shaka-player",
    "author": "Google",
    "maintainers": [
        {
            "name": "Joey Parrish"
        }
    ],
    "devDependencies": {
        "array-includes": "^3.0.2",
        "es6-shim": "^0.35.2",
        "esprima": "^3.1.3",
        "htmlhint": "yaniswang/HTMLHint#152a114f",
        "in-publish": "2.x",
        "jasmine-ajax": "3.3.x",
        "jasmine-core": "2.4.x",
        "karma": "~1.1.2",
        "karma-chrome-launcher": "~1.0.1",
        "karma-coverage": "~1.1.1",
        "karma-edge-launcher": "^0.2.0",
        "karma-firefox-launcher": "~1.0.0",
        "karma-ie-launcher": "~1.0.0",
        "karma-jasmine": "~1.0.2",
        "karma-jasmine-ajax": "~0.1.13",
        "karma-opera-launcher": "~1.0.0",
        "karma-safari-launcher": "~1.0.0",
        "karma-spec-reporter": "~0.0.26",
        "karma-webdriver-launcher": "~1.0.4",
        "requirejs": "2.x",
        "rimraf": "2.x",
        "sprintf-js": "1.x",
        "useragent": "^2.1.11"
    },
    "main": "dist/shaka-player.compiled.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/google/shaka-player.git"
    },
    "bugs": {
        "url": "https://github.com/google/shaka-player/issues"
    },
    "license": "Apache-2.0",
    "scripts": {
        "prepublish": "in-publish && python ./build/checkversion.py && python ./build/all.py || not-in-publish"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
