# npmdoc-git-scripts

#### basic api documentation for  [git-scripts (v0.2.1)](https://github.com/nkzawa/git-scripts)  [![npm package](https://img.shields.io/npm/v/npmdoc-git-scripts.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-git-scripts) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-git-scripts.svg)](https://travis-ci.org/npmdoc/node-npmdoc-git-scripts)

#### Git hooks integration for Node.js projects

[![NPM](https://nodei.co/npm/git-scripts.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/git-scripts)

- [https://npmdoc.github.io/node-npmdoc-git-scripts/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-git-scripts/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-git-scripts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-git-scripts/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-git-scripts/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-git-scripts/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Naoyuki Kanezawa"
    },
    "bin": {
        "git-scripts": "./bin/git-scripts"
    },
    "bugs": {
        "url": "https://github.com/nkzawa/git-scripts/issues"
    },
    "dependencies": {
        "commander": "2.6.0"
    },
    "description": "Git hooks integration for Node.js projects",
    "devDependencies": {
        "chai": "~1.10.0",
        "git-scripts": "latest",
        "mktmpdir": "~0.1.1",
        "mocha": "~2.1.0",
        "rimraf": "~2.2.8"
    },
    "directories": {},
    "dist": {
        "shasum": "a45cb72dfa4e1208de5d9f674c0560c52da331d7",
        "tarball": "https://registry.npmjs.org/git-scripts/-/git-scripts-0.2.1.tgz"
    },
    "git": {
        "scripts": {
            "pre-commit": "npm test"
        }
    },
    "gitHead": "8e7d2acd664d99da973f7b376714e1e353fb7eba",
    "homepage": "https://github.com/nkzawa/git-scripts",
    "keywords": [
        "git",
        "hooks",
        "npm",
        "scripts"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "nkzawa"
        }
    ],
    "name": "git-scripts",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/nkzawa/git-scripts.git"
    },
    "scripts": {
        "postinstall": "./bin/install",
        "postupdate": "./bin/install",
        "prepublish": "make build",
        "preuninstall": "./bin/uninstall",
        "test": "make test"
    },
    "version": "0.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
