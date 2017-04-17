# test coverage for  [email-templates (v2.5.4)](https://github.com/niftylettuce/node-email-templates)  [![npm package](https://img.shields.io/npm/v/npmtest-email-templates.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-email-templates) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-email-templates.svg)](https://travis-ci.org/npmtest/node-npmtest-email-templates)
#### Node.js module for rendering beautiful emails with ejs, jade, swig, hbs, or handlebars templates and email-friendly inline CSS using juice.

[![NPM](https://nodei.co/npm/email-templates.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/email-templates)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-email-templates/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-email-templates/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-email-templates/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-email-templates/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-email-templates/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-email-templates/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-email-templates/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-email-templates/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-email-templates/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-email-templates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-email-templates/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-email-templates/build/test-report.html](https://npmtest.github.io/node-npmtest-email-templates/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-email-templates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-email-templates/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-email-templates/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-email-templates/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-email-templates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-email-templates/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-email-templates/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-email-templates/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Baugh"
    },
    "bugs": {
        "url": "https://github.com/niftylettuce/node-email-templates/issues/new"
    },
    "contributors": [
        {
            "name": "Nick Baugh"
        },
        {
            "name": "Andrea Baccega"
        },
        {
            "name": "Nic Jansma",
            "url": "http://nicj.net"
        },
        {
            "name": "Jason Sims"
        },
        {
            "name": "Miguel Mota"
        },
        {
            "name": "Jeduan Cornejo"
        },
        {
            "name": "Alberto Souza"
        }
    ],
    "dependencies": {
        "bluebird": "^3.0.0",
        "consolidate": "^0.14.2",
        "debug": "^2.2.0",
        "glob": "^6.0.0",
        "juice": "^2.0.0",
        "lodash": "^4.0.1"
    },
    "description": "Node.js module for rendering beautiful emails with ejs, jade, swig, hbs, or handlebars templates and email-friendly inline CSS using juice.",
    "devDependencies": {
        "async": "^1.5.0",
        "babel-cli": "^6.4.5",
        "babel-preset-es2015": "^6.3.13",
        "babel-register": "^6.4.3",
        "chai": "^3.0.0",
        "dustjs-linkedin": "^2.4.0",
        "ejs": "^2.3.0",
        "handlebars": "^4.0.0",
        "istanbul": "^0.4.2",
        "jade": "^1.3.1",
        "less": "^2.5.0",
        "mkdirp": "^0.5.1",
        "mocha": "^2.1.0",
        "node-sass": "^3.1.1",
        "nodemailer": "^1.3.4",
        "nodemailer-wellknown": "^0.1.5",
        "postmark": "^1.0.0",
        "rimraf": "^2.2.8",
        "sinon": "^1.10.2",
        "sinon-chai": "^2.7.0",
        "standard": "^5.4.1",
        "styl": "^0.2.7",
        "stylus": "^0.53.0",
        "swig": "^1.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5f8995f63802688f5afd5aa50ee7587f4e1c9440",
        "tarball": "https://registry.npmjs.org/email-templates/-/email-templates-2.5.4.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "cfb16da5c92d788df8dbf8b487a973a1b671cf57",
    "homepage": "https://github.com/niftylettuce/node-email-templates",
    "keywords": [
        "node-email-templates",
        "windows",
        "ejs",
        "email",
        "templates",
        "email-templates",
        "juice",
        "inline",
        "i18n",
        "css"
    ],
    "license": "MIT",
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "niftylettuce"
        },
        {
            "name": "jasonsims"
        },
        {
            "name": "jeduan"
        }
    ],
    "name": "email-templates",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/niftylettuce/node-email-templates.git"
    },
    "scripts": {
        "compile": "babel src --modules common --out-dir lib",
        "prepublish": "npm run compile && npm prune",
        "test": "standard && mocha",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly",
        "watch": "babel src --watch --modules common --out-dir lib --source-maps true"
    },
    "standard": {
        "ignore": [
            "lib",
            "examples"
        ]
    },
    "version": "2.5.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
