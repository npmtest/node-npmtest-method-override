# test coverage for  [method-override (v2.3.8)](https://github.com/expressjs/method-override#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-method-override.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-method-override) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-method-override.svg)](https://travis-ci.org/npmtest/node-npmtest-method-override)
#### Override HTTP verbs

[![NPM](https://nodei.co/npm/method-override.png?downloads=true)](https://www.npmjs.com/package/method-override)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-method-override/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-method-override/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-method-override/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-method-override/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-method-override/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-method-override/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-method-override/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-method-override/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-method-override/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-method-override/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-method-override%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-method-override/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-method-override/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-method-override%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-method-override/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-method-override/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-method-override/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/method-override/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "Jonathan Ong",
            "email": "me@jongleberry.com",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "debug": "2.6.3",
        "methods": "~1.1.2",
        "parseurl": "~1.3.1",
        "vary": "~1.1.0"
    },
    "description": "Override HTTP verbs",
    "devDependencies": {
        "eslint": "3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "178234bf4bab869f89df9444b06fc6147b44828c",
        "tarball": "https://registry.npmjs.org/method-override/-/method-override-2.3.8.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "96422fdbc34d01d4d68624823aa71de345cea9da",
    "homepage": "https://github.com/expressjs/method-override#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "defunctzombie",
            "email": "shtylman@gmail.com"
        },
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "fishrock123",
            "email": "fishrock123@rocketmail.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "mscdex",
            "email": "mscdex@mscdex.net"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "method-override",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/method-override.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --check-leaks --reporter spec --bail test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --check-leaks --reporter dot test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --check-leaks --reporter spec test/"
    },
    "version": "2.3.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
