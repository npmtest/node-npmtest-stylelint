# test coverage for  [stylelint (v7.10.1)](https://stylelint.io)  [![npm package](https://img.shields.io/npm/v/npmtest-stylelint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stylelint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stylelint.svg)](https://travis-ci.org/npmtest/node-npmtest-stylelint)
#### A mighty, modern CSS linter.

[![NPM](https://nodei.co/npm/stylelint.png?downloads=true)](https://www.npmjs.com/package/stylelint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stylelint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stylelint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stylelint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stylelint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stylelint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stylelint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stylelint/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stylelint/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-stylelint/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-stylelint/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-stylelint%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stylelint/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stylelint/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-stylelint%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stylelint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stylelint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stylelint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "David Clark",
        "Maxime Thirouin",
        "Richard Hallows"
    ],
    "bin": {
        "stylelint": "bin/stylelint.js"
    },
    "bugs": {
        "url": "https://github.com/stylelint/stylelint/issues"
    },
    "dependencies": {
        "autoprefixer": "^6.0.0",
        "balanced-match": "^0.4.0",
        "chalk": "^1.1.1",
        "colorguard": "^1.2.0",
        "cosmiconfig": "^2.1.1",
        "debug": "^2.6.0",
        "doiuse": "^2.4.1",
        "execall": "^1.0.0",
        "file-entry-cache": "^2.0.0",
        "get-stdin": "^5.0.0",
        "globby": "^6.0.0",
        "globjoin": "^0.1.4",
        "html-tags": "^1.1.1",
        "ignore": "^3.2.0",
        "imurmurhash": "^0.1.4",
        "known-css-properties": "^0.0.7",
        "lodash": "^4.17.4",
        "log-symbols": "^1.0.2",
        "meow": "^3.3.0",
        "micromatch": "^2.3.11",
        "normalize-selector": "^0.2.0",
        "postcss": "^5.0.20",
        "postcss-less": "^0.14.0",
        "postcss-media-query-parser": "^0.2.0",
        "postcss-reporter": "^3.0.0",
        "postcss-resolve-nested-selector": "^0.1.1",
        "postcss-scss": "^0.4.0",
        "postcss-selector-parser": "^2.1.1",
        "postcss-value-parser": "^3.1.1",
        "resolve-from": "^2.0.0",
        "specificity": "^0.3.0",
        "string-width": "^2.0.0",
        "style-search": "^0.1.0",
        "stylehacks": "^2.3.2",
        "sugarss": "^0.2.0",
        "svg-tags": "^1.0.0",
        "table": "^4.0.1"
    },
    "description": "A mighty, modern CSS linter.",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "common-tags": "^1.3.0",
        "coveralls": "^2.11.16",
        "cp-file": "^4.1.1",
        "d3-queue": "^3.0.3",
        "eslint": "~3.19.0",
        "eslint-config-stylelint": "^6.0.0",
        "file-exists-promise": "^1.0.2",
        "flow-bin": "^0.42.0",
        "fs-promise": "^2.0.0",
        "jest": "^19.0.1",
        "npm-run-all": "^4.0.0",
        "npmpub": "^3.0.1",
        "pify": "^2.3.0",
        "postcss-import": "^9.0.0",
        "postcss-safe-parser": "^2.0.0",
        "remark-cli": "^3.0.0",
        "remark-preset-lint-consistent": "^2.0.0",
        "remark-preset-lint-recommended": "^2.0.0",
        "remark-validate-links": "^6.0.0",
        "request": "^2.69.0",
        "sinon": "^2.0.0",
        "strip-ansi": "^3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "209a7ce5e781fc2a62489fbb31ec0201ec675db2",
        "tarball": "https://registry.npmjs.org/stylelint/-/stylelint-7.10.1.tgz"
    },
    "engines": {
        "node": ">=4.2.1"
    },
    "eslintConfig": {
        "extends": [
            "stylelint"
        ],
        "globals": {
            "testRule": true
        }
    },
    "files": [
        "bin",
        "CONTRIBUTING.md",
        "decls/*.js",
        "docs",
        "lib",
        "!**/__tests__"
    ],
    "gitHead": "d76c6d1358917fe06f56710f71ddfc32ebd6b759",
    "greenkeeper": {
        "label": "PR: review needed"
    },
    "homepage": "https://stylelint.io",
    "jest": {
        "collectCoverage": false,
        "collectCoverageFrom": [
            "lib/**/*.js"
        ],
        "coverageDirectory": "./.coverage/",
        "coverageReporters": [
            "lcov",
            "text-summary"
        ],
        "coverageThreshold": {
            "global": {
                "branches": 75,
                "functions": 75,
                "lines": 75,
                "statements": 75
            }
        },
        "setupFiles": [
            "./jest-setup.js"
        ],
        "testEnvironment": "node",
        "roots": [
            "lib",
            "system-tests"
        ],
        "testRegex": ".*\\.test\\.js$|rules/.*/__tests__/.*\\.js$"
    },
    "keywords": [
        "css",
        "less",
        "scss",
        "sugarss",
        "lint",
        "linter",
        "stylelint"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "davidtheclark",
            "email": "david.dave.clark@gmail.com"
        },
        {
            "name": "jeddy3",
            "email": "npm@richardhallows.com"
        },
        {
            "name": "moox",
            "email": "m@moox.io"
        }
    ],
    "name": "stylelint",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "remarkConfig": {
        "plugins": [
            "preset-lint-recommended",
            "preset-lint-consistent",
            [
                "validate-links",
                {
                    "repository": "stylelint/stylelint"
                }
            ]
        ]
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stylelint/stylelint.git"
    },
    "scripts": {
        "benchmark-rule": "node scripts/benchmark-rule.js",
        "flow": "flow",
        "jest": "jest",
        "lint": "npm-run-all --parallel lint:*",
        "lint:js": "eslint . --cache",
        "lint:md": "remark . --quiet --frail",
        "pretest": "npm-run-all --serial lint flow",
        "release": "npmpub",
        "test": "jest --coverage",
        "watch": "jest --watch"
    },
    "version": "7.10.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
