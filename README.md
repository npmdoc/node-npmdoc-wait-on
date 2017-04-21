# npmdoc-wait-on

#### api documentation for  wait-on (v2.0.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-wait-on.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-wait-on) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-wait-on.svg)](https://travis-ci.org/npmdoc/node-npmdoc-wait-on)

#### wait-on is a cross platform command line utility and Node.js API which will wait for files, ports, sockets, and http(s) resources to become available

[![NPM](https://nodei.co/npm/wait-on.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wait-on)

- [https://npmdoc.github.io/node-npmdoc-wait-on/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wait-on/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wait-on/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wait-on/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-wait-on/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-wait-on/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "wait-on",
    "description": "wait-on is a cross platform command line utility and Node.js API which will wait for files, ports, sockets, and http(s) resources to become available",
    "version": "2.0.2",
    "main": "lib/wait-on",
    "bin": {
        "wait-on": "bin/wait-on"
    },
    "author": "Jeff Barczewski <info@codewinds.com>",
    "repository": {
        "type": "git",
        "url": "http://github.com/jeffbski/wait-on.git"
    },
    "bugs": {
        "url": "http://github.com/jeffbski/wait-on/issues"
    },
    "license": "MIT",
    "scripts": {
        "test": "mocha 'test/**/*.mocha.js'"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "devDependencies": {
        "accum": "^0.3.6",
        "expect": "^1.8.0",
        "mocha": "^3.1.2",
        "temp": "^0.8.3"
    },
    "dependencies": {
        "core-js": "^2.4.1",
        "joi": "^9.2.0",
        "minimist": "^1.2.0",
        "request": "^2.78.0",
        "rx": "^4.1.0"
    },
    "keywords": [
        "wait",
        "delay",
        "cli",
        "files",
        "tcp",
        "ports",
        "sockets",
        "http",
        "exist",
        "ready",
        "available",
        "portable",
        "cross-platform",
        "unix",
        "linux",
        "windows",
        "win32",
        "osx"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
