# npmdoc-ddos

#### api documentation for  [ddos (v0.1.16)](https://github.com/rook2pawn/node-ddos)  [![npm package](https://img.shields.io/npm/v/npmdoc-ddos.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ddos) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ddos.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ddos)

#### Configurable Denial-Of-Service prevention for http services

[![NPM](https://nodei.co/npm/ddos.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ddos)

- [https://npmdoc.github.io/node-npmdoc-ddos/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ddos/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ddos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ddos/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ddos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ddos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Wee",
        "url": "http://rook2pawn.com"
    },
    "bugs": {
        "url": "https://github.com/rook2pawn/node-ddos/issues"
    },
    "dependencies": {
        "hashish": "",
        "response": ""
    },
    "description": "Configurable Denial-Of-Service prevention for http services",
    "devDependencies": {
        "body-parser": "^1.15.2",
        "express": "",
        "koa": "^1.1.2",
        "mocha": "^2.3.4",
        "queuelib": "",
        "request": "",
        "supertest": "^1.1.0",
        "tape": ""
    },
    "directories": {},
    "dist": {
        "shasum": "45c7cc77ebcd3f7a41a500d23d96dbeb2bca34c9",
        "tarball": "https://registry.npmjs.org/ddos/-/ddos-0.1.16.tgz"
    },
    "gitHead": "2640c00a03ac8378b71c135d49bf136db871dd54",
    "homepage": "https://github.com/rook2pawn/node-ddos",
    "keywords": [
        "ddos",
        "rate",
        "limiting"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rook2pawn"
        }
    ],
    "name": "ddos",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/rook2pawn/node-ddos.git"
    },
    "scripts": {
        "test": "tape test/test-whitelist.js && tape test/test-post.js && tape test/test-express.js && mocha --harmony test/test-koa.js"
    },
    "version": "0.1.16"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
