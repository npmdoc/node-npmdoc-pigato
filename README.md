# npmdoc-pigato

#### basic api documentation for  [pigato (v0.0.46)](https://github.com/prdn/pigato)  [![npm package](https://img.shields.io/npm/v/npmdoc-pigato.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pigato) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pigato.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pigato)

#### An high-performance Node.js microservices framework based on ZeroMQ

[![NPM](https://nodei.co/npm/pigato.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pigato)

- [https://npmdoc.github.io/node-npmdoc-pigato/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pigato/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pigato/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pigato/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pigato/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pigato/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pigato",
    "version": "0.0.46",
    "private": false,
    "description": "An high-performance Node.js microservices framework based on ZeroMQ",
    "author": "prdn <paolo.ardoino@gmail.com> (http://ardoino.com/)",
    "keywords": [
        "pigato",
        "nodejs",
        "zmq",
        "zeromq",
        "0mq",
        "request-reply",
        "amqp",
        "mdp",
        "micro-services"
    ],
    "dependencies": {
        "async": "~1.5.2",
        "debug": "~2.2.0",
        "es6-shim": "^0.33.13",
        "lodash": "~4.2.1",
        "node-uuid": "~1.4.7",
        "readable-stream": "2.0.4",
        "semver": "^5.0.3",
        "zmq": "~2.15.2"
    },
    "engine": {
        "node": ">=0.10"
    },
    "main": "index.js",
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "devDependencies": {
        "chai": "~3.2.0",
        "mocha": "~2.2.5"
    },
    "scripts": {
        "test": "make test",
        "lint": "eslint --config .eslintrc --fix index.js lib/ test/"
    },
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/prdn/pigato.git"
    },
    "bugs": {
        "url": "https://github.com/prdn/pigato/issues"
    },
    "homepage": "https://github.com/prdn/pigato",
    "optionalDependencies": {
        "eslint": "~1.6.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
