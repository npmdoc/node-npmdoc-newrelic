# npmdoc-newrelic

#### api documentation for  [newrelic (v1.38.2)](http://github.com/newrelic/node-newrelic)  [![npm package](https://img.shields.io/npm/v/npmdoc-newrelic.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-newrelic) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-newrelic.svg)](https://travis-ci.org/npmdoc/node-npmdoc-newrelic)

#### New Relic agent

[![NPM](https://nodei.co/npm/newrelic.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/newrelic)

- [https://npmdoc.github.io/node-npmdoc-newrelic/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-newrelic/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-newrelic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-newrelic/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-newrelic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-newrelic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "newrelic",
    "version": "1.38.2",
    "author": "New Relic Node.js agent team <nodejs@newrelic.com>",
    "licenses": [
        {
            "type": "proprietary",
            "url": "https://raw.github.com/newrelic/node-newrelic/master/LICENSE"
        }
    ],
    "contributors": [
        {
            "name": "Saxon D'Aubin",
            "web": "http://newrelic.com"
        },
        {
            "name": "Forrest L Norvell",
            "web": "http://newrelic.com/"
        },
        {
            "name": "Jacob Groundwater",
            "web": "https://newrelic.com"
        },
        {
            "name": "Wraithan (Chris McDonald)",
            "web": "https://newrelic.com"
        },
        {
            "name": "Michael Hayes",
            "web": "https://newrelic.com"
        },
        {
            "name": "Bryan Clement",
            "web": "https://newrelic.com"
        },
        {
            "name": "Jeff Olfert",
            "web": "https://newrelic.com"
        },
        {
            "name": "Wilson Bilkovich",
            "web": "https://newrelic.com"
        },
        {
            "name": "Jonathan Merrill",
            "web": "https://newrelic.com"
        },
        {
            "name": "Martin Kuba",
            "web": "https://newrelic.com"
        },
        {
            "name": "Tim Krajcar",
            "web": "https://newrelic.com"
        },
        {
            "name": "Eric Wang",
            "web": "https://newrelic.com"
        },
        {
            "name": "Natalie Wolfe",
            "web": "https://newrelic.com"
        },
        {
            "name": "Seth Shober",
            "web": "https://newrelic.com"
        }
    ],
    "description": "New Relic agent",
    "keywords": [
        "apm",
        "performance",
        "monitoring",
        "instrumentation",
        "debugging",
        "profiling"
    ],
    "homepage": "http://github.com/newrelic/node-newrelic",
    "engines": {
        "node": ">=0.6.0"
    },
    "directories": {
        "lib": "lib"
    },
    "scripts": {
        "test": "make test"
    },
    "bin": {
        "newrelic-naming-rules": "./bin/test-naming-rules.js"
    },
    "dependencies": {
        "concat-stream": "^1.5.0",
        "https-proxy-agent": "^0.3.5",
        "json-stringify-safe": "^5.0.0",
        "readable-stream": "^1.1.13",
        "semver": "^5.3.0"
    },
    "bundledDependencies": [
        "concat-stream",
        "https-proxy-agent",
        "json-stringify-safe",
        "readable-stream",
        "semver"
    ],
    "devDependencies": {
        "async": "^2.1.4",
        "eslint": "^2.9.0",
        "mocha": "*",
        "tap": "^9.0.3"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/newrelic/node-newrelic.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
