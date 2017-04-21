# npmdoc-reglite

#### api documentation for  reglite (v0.1.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-reglite.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-reglite) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-reglite.svg)](https://travis-ci.org/npmdoc/node-npmdoc-reglite)

#### A private npm registry.

[![NPM](https://nodei.co/npm/reglite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reglite)

- [https://npmdoc.github.io/node-npmdoc-reglite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reglite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reglite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reglite/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-reglite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-reglite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "reglite",
    "version": "0.1.2",
    "description": "A private npm registry.",
    "main": "app.js",
    "scripts": {
        "test": "mocha test"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/lxe/reglite"
    },
    "keywords": [
        "npm",
        "registry",
        "node",
        "proxy"
    ],
    "author": "Aleksey Smolenchuk <lxe@lxe.co>",
    "license": "ISC",
    "dependencies": {
        "async": "^0.9.0",
        "raw-body": "^1.3.0",
        "request": "^2.40.0",
        "shasum": "^1.0.0"
    },
    "bin": {
        "reglite": "./app.js"
    },
    "devDependencies": {
        "mocha": "^1.21.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
