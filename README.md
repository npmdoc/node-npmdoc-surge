# npmdoc-surge

#### api documentation for  [surge (v0.19.0)](https://github.com/sintaxi/surge#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-surge.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-surge) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-surge.svg)](https://travis-ci.org/npmdoc/node-npmdoc-surge)

#### CDN for front-end developers

[![NPM](https://nodei.co/npm/surge.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/surge)

- [https://npmdoc.github.io/node-npmdoc-surge/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-surge/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-surge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-surge/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-surge/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-surge/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brock Whitten"
    },
    "bin": {
        "surge": "./lib/cli.js"
    },
    "bugs": {
        "url": "https://github.com/sintaxi/surge/issues"
    },
    "dependencies": {
        "du": "0.1.0",
        "fstream-ignore": "1.0.2",
        "is-domain": "0.0.1",
        "minimist": "1.1.1",
        "moniker": "0.1.2",
        "netrc": "0.1.4",
        "progress": "1.1.8",
        "prompt": "~0.2.14",
        "read": "1.0.5",
        "request": "2.40.0",
        "split": "0.3.1",
        "surge-ignore": "0.2.0",
        "tar": "1.0.0",
        "tar.gz": "0.1.1",
        "url-parse-as-address": "1.0.0"
    },
    "description": "CDN for front-end developers",
    "devDependencies": {
        "commander": "2.9.0",
        "mocha": "*",
        "nixt": "0.4.1",
        "should": "7.1.0",
        "yargs": "3.30.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ae430df0f2832ba24aa379b7766586fe68b7239c",
        "tarball": "https://registry.npmjs.org/surge/-/surge-0.19.0.tgz"
    },
    "gitHead": "0d7e643c48cbe450831ee6dba7e9441ba7361f5e",
    "homepage": "https://github.com/sintaxi/surge#readme",
    "ignore": [
        "test"
    ],
    "license": "ISC",
    "main": "./lib/surge.js",
    "maintainers": [
        {
            "name": "kennethormandy"
        },
        {
            "name": "sintaxi"
        }
    ],
    "name": "surge",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sintaxi/surge.git"
    },
    "scripts": {
        "test": "mocha -t 5000",
        "test:local": "ENDPOINT='localhost:5001' ./node_modules/.bin/mocha"
    },
    "version": "0.19.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
