# npmdoc-expand-tilde

#### basic api documentation for  [expand-tilde (v2.0.2)](https://github.com/jonschlinkert/expand-tilde)  [![npm package](https://img.shields.io/npm/v/npmdoc-expand-tilde.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-expand-tilde) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-expand-tilde.svg)](https://travis-ci.org/npmdoc/node-npmdoc-expand-tilde)

#### Bash-like tilde expansion for node.js. Expands a leading tilde in a file path to the user home directory, or `~+` to the cwd.

[![NPM](https://nodei.co/npm/expand-tilde.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/expand-tilde)

- [https://npmdoc.github.io/node-npmdoc-expand-tilde/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-expand-tilde/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-expand-tilde/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-expand-tilde/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-expand-tilde/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-expand-tilde/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bugs": {
        "url": "https://github.com/jonschlinkert/expand-tilde/issues"
    },
    "dependencies": {
        "homedir-polyfill": "^1.0.1"
    },
    "description": "Bash-like tilde expansion for node.js. Expands a leading tilde in a file path to the user home directory, or '~+' to the cwd.",
    "devDependencies": {
        "gulp-format-md": "^0.1.9",
        "is-windows": "^0.2.0",
        "mocha": "^2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "97e801aa052df02454de46b02bf621642cdc8502",
        "tarball": "https://registry.npmjs.org/expand-tilde/-/expand-tilde-2.0.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "2389f5d93903c43bc26ed57b02a24b432d1dee89",
    "homepage": "https://github.com/jonschlinkert/expand-tilde",
    "keywords": [
        "cwd",
        "expand",
        "expansion",
        "filepath",
        "home",
        "path",
        "pwd",
        "tilde",
        "user",
        "userhome"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "doowb"
        },
        {
            "name": "jonschlinkert"
        }
    ],
    "name": "expand-tilde",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonschlinkert/expand-tilde.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "verb": {
        "run": true,
        "toc": false,
        "layout": "default",
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "related": {
            "list": [
                "braces",
                "expand-brackets",
                "is-glob",
                "micromatch"
            ]
        },
        "reflinks": [
            "verb"
        ],
        "lint": {
            "reflinks": true
        }
    },
    "version": "2.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
