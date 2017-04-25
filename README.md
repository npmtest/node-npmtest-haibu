# npmtest-haibu

#### basic test coverage for  [haibu (v0.10.3)](https://github.com/nodejitsu/haibu#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-haibu.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-haibu) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-haibu.svg)](https://travis-ci.org/npmtest/node-npmtest-haibu)

#### A node.js application server - spawn your own node.js clouds, on your own hardware

[![NPM](https://nodei.co/npm/haibu.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/haibu)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-haibu/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-haibu/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-haibu/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-haibu/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-haibu/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-haibu/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-haibu/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-haibu/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-haibu/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-haibu/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-haibu/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-haibu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-haibu/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-haibu/build/test-report.html](https://npmtest.github.io/node-npmtest-haibu/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-haibu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-haibu/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-haibu/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-haibu/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-haibu/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-haibu/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-haibu/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-haibu/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nodejitsu Inc."
    },
    "bin": {
        "haibu": "./bin/haibu"
    },
    "bugs": {
        "url": "https://github.com/nodejitsu/haibu/issues"
    },
    "dependencies": {
        "cloudfiles": "0.3.3",
        "eyes": "0.1.7",
        "flatiron": "0.3.4",
        "forever-monitor": "1.1.0",
        "haibu-api": "0.9.0",
        "haibu-carapace": "0.7.1",
        "knox": "0.5.4",
        "npm": "1.3.4",
        "optimist": "~0.3.5",
        "pkginfo": "0.2.3",
        "request": "~2.14.0",
        "semver": "~1.1.4",
        "tar": "0.1.13",
        "union": "0.3.7",
        "winston": "~0.7.2"
    },
    "description": "A node.js application server - spawn your own node.js clouds, on your own hardware",
    "devDependencies": {
        "vows": "~0.7.0",
        "winston-loggly": "0.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "660d150e880b6dd54d1a2cbbe7afd5e552fe4004",
        "tarball": "https://registry.npmjs.org/haibu/-/haibu-0.10.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "homepage": "https://github.com/nodejitsu/haibu#readme",
    "keywords": [
        "cloud computing",
        "automated deployment",
        "platform-as-a-service"
    ],
    "main": "./lib/haibu",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "bradleymeck"
        },
        {
            "name": "avianflu"
        },
        {
            "name": "mmalecki"
        },
        {
            "name": "jcrugzz"
        }
    ],
    "name": "haibu",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nodejitsu/haibu.git"
    },
    "scripts": {
        "test": "vows test/*/*-test.js --isolate --spec"
    },
    "version": "0.10.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
