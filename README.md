# api documentation for  [ddos (v0.1.16)](https://github.com/rook2pawn/node-ddos)  [![npm package](https://img.shields.io/npm/v/npmdoc-ddos.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ddos) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ddos.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ddos)
#### Configurable Denial-Of-Service prevention for http services

[![NPM](https://nodei.co/npm/ddos.png?downloads=true)](https://www.npmjs.com/package/ddos)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ddos/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-ddos_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ddos/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ddos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ddos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Wee",
        "email": "rook2pawn@gmail.com",
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
            "name": "rook2pawn",
            "email": "rook2pawn@gmail.com"
        }
    ],
    "name": "ddos",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module ddos](#apidoc.module.ddos)



# <a name="apidoc.module.ddos"></a>[module ddos](#apidoc.module.ddos)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
