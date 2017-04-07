# api documentation for  [npm-run-all (v4.0.2)](https://github.com/mysticatea/npm-run-all)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-run-all.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-run-all) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-run-all.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-run-all)
#### A CLI tool to run multiple npm-scripts in parallel or sequential.

[![NPM](https://nodei.co/npm/npm-run-all.png?downloads=true)](https://www.npmjs.com/package/npm-run-all)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-run-all/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-npm-run-all%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-run-all/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-run-all/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-run-all/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Toru Nagashima"
    },
    "bin": {
        "run-p": "bin/run-p/index.js",
        "run-s": "bin/run-s/index.js",
        "npm-run-all": "bin/npm-run-all/index.js"
    },
    "bugs": {
        "url": "https://github.com/mysticatea/npm-run-all/issues"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "cross-spawn": "^5.0.1",
        "minimatch": "^3.0.2",
        "ps-tree": "^1.0.1",
        "read-pkg": "^2.0.0",
        "shell-quote": "^1.6.1",
        "string.prototype.padend": "^3.0.0"
    },
    "description": "A CLI tool to run multiple npm-scripts in parallel or sequential.",
    "devDependencies": {
        "@types/node": "^4.0.30",
        "babel-preset-power-assert": "^1.0.0",
        "babel-register": "^6.4.3",
        "codecov": "^1.0.1",
        "eslint": "^3.12.2",
        "eslint-config-mysticatea": "^7.0.1",
        "jsdoc": "^3.4.0",
        "mocha": "^3.2.0",
        "nyc": "^10.0.0",
        "power-assert": "^1.2.0",
        "rimraf": "^2.4.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a84669348e6db6ccbe052200b4cdb6bfe034a4fe",
        "tarball": "https://registry.npmjs.org/npm-run-all/-/npm-run-all-4.0.2.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "files": [
        "bin",
        "lib"
    ],
    "gitHead": "46cfd570cc74abec3655b107925ddbe463fe5c88",
    "homepage": "https://github.com/mysticatea/npm-run-all",
    "keywords": [
        "cli",
        "command",
        "commandline",
        "tool",
        "npm",
        "npm-scripts",
        "run",
        "sequential",
        "serial",
        "parallel",
        "task"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "mysticatea",
            "email": "star.ctor@gmail.com"
        }
    ],
    "name": "npm-run-all",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mysticatea/npm-run-all.git"
    },
    "scripts": {
        "_mocha": "mocha \"test/*.js\" --compilers js:babel-register --timeout 60000",
        "clean": "rimraf .nyc_output coverage jsdoc \"test-workspace/{build,test.txt}\"",
        "codecov": "nyc report -r lcovonly && codecov",
        "docs": "jsdoc -c jsdoc.json",
        "lint": "eslint bin lib scripts test \"test-workspace/tasks/*.js\"",
        "postversion": "git push && git push --tags",
        "pretest": "node scripts/make-slink.js && npm run lint",
        "preversion": "npm test",
        "test": "nyc npm run _mocha",
        "watch": "npm run _mocha -- --watch --growl"
    },
    "version": "4.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module npm-run-all](#apidoc.module.npm-run-all)



# <a name="apidoc.module.npm-run-all"></a>[module npm-run-all](#apidoc.module.npm-run-all)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
