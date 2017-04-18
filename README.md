# npmtest-sails-generate-frontend

#### test coverage for  sails-generate-frontend (v0.12.3)  [![npm package](https://img.shields.io/npm/v/npmtest-sails-generate-frontend.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails-generate-frontend) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails-generate-frontend.svg)](https://travis-ci.org/npmtest/node-npmtest-sails-generate-frontend)

#### Default generator for frontend code files in new Sails projects. Creates the default contents of the `assets/` folder when you run `sails new` on the command-line.  Also creates a subset of the boilerplate Grunt task files (in `tasks/`); specifically, the

[![NPM](https://nodei.co/npm/sails-generate-frontend.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-generate-frontend)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails-generate-frontend/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails-generate-frontend/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails-generate-frontend/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/test-report.html](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails-generate-frontend/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-generate-frontend/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-generate-frontend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-generate-frontend/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails-generate-frontend/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "balderdashy"
    },
    "dependencies": {
        "lodash": "2.4.1",
        "merge-defaults": "0.1.0",
        "sails-generate-sails.io.js": "^0.14.0"
    },
    "description": "Default generator for frontend code files in new Sails projects. Creates the default contents of the 'assets/' folder when you run 'sails new' on the command-line.  Also creates a subset of the boilerplate Grunt task files (in 'tasks/'); specifically, the",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "5e029d8abdc2f6007b56d09892be44013ae457dc",
        "tarball": "https://registry.npmjs.org/sails-generate-frontend/-/sails-generate-frontend-0.12.3.tgz"
    },
    "gitHead": "83c07ecf5c831f9858587c8f39de1a13ec16c167",
    "keywords": [
        "frontend",
        "generator",
        "sails",
        "generate",
        "plugin"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "balderdashy"
        },
        {
            "name": "sgress454"
        },
        {
            "name": "mikermcneil"
        }
    ],
    "name": "sails-generate-frontend",
    "optionalDependencies": {},
    "repo": "https://github.com/balderdashy/sails-generate-frontend",
    "sailsGenerator": {
        "type": "frontend",
        "behavior": "overrides 'sails generate frontend'",
        "sailsVersion": "~0.10.0"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.12.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
