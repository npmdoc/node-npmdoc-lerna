# npmdoc-lerna

#### basic api documentation for  [lerna (v1.1.3)](https://github.com/sebmck/lerna#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-lerna.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lerna) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lerna.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lerna)

#### Tool for managing JavaScript projects with multiple packages

[![NPM](https://nodei.co/npm/lerna.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lerna)

- [https://npmdoc.github.io/node-npmdoc-lerna/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lerna/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lerna/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lerna/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lerna/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lerna/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian McKenzie"
    },
    "bin": {
        "lerna": "./bin/lerna.js"
    },
    "bugs": {
        "url": "https://github.com/sebmck/lerna/issues"
    },
    "dependencies": {
        "async": "^1.5.0",
        "chalk": "^1.1.1",
        "mkdirp": "^0.5.1",
        "pad": "^1.0.0",
        "progress": "^1.1.8",
        "readline-sync": "^1.2.21",
        "rimraf": "^2.4.4",
        "semver": "^5.1.0"
    },
    "description": "Tool for managing JavaScript projects with multiple packages",
    "devDependencies": {
        "eslint": "^1.10.3"
    },
    "directories": {},
    "dist": {
        "shasum": "75c12247012a842221259337c67896616371cac8",
        "tarball": "https://registry.npmjs.org/lerna/-/lerna-1.1.3.tgz"
    },
    "gitHead": "2de7742f8a077caeef8d34a81ea65f57ec9753ab",
    "homepage": "https://github.com/sebmck/lerna#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "hzoo"
        },
        {
            "name": "sebmck"
        },
        {
            "name": "thejameskyle"
        }
    ],
    "name": "lerna",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sebmck/lerna.git"
    },
    "scripts": {
        "ci": "npm run lint",
        "lint": "eslint lib"
    },
    "version": "1.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
