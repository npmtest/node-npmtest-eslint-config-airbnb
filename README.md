# test coverage for  [eslint-config-airbnb (v14.1.0)](https://github.com/airbnb/javascript)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-config-airbnb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-config-airbnb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-config-airbnb.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-config-airbnb)
#### Airbnb's ESLint config, following our styleguide

[![NPM](https://nodei.co/npm/eslint-config-airbnb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-config-airbnb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-config-airbnb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-config-airbnb/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-config-airbnb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jake Teton-Landis",
        "url": "https://twitter.com/@jitl"
    },
    "bugs": {
        "url": "https://github.com/airbnb/javascript/issues"
    },
    "contributors": [
        {
            "name": "Jake Teton-Landis",
            "url": "https://twitter.com/jitl"
        },
        {
            "name": "Jordan Harband",
            "url": "http://ljharb.codes"
        },
        {
            "name": "Harrison Shoff",
            "url": "https://twitter.com/hshoff"
        }
    ],
    "dependencies": {
        "eslint-config-airbnb-base": "^11.1.0"
    },
    "description": "Airbnb's ESLint config, following our styleguide",
    "devDependencies": {
        "babel-preset-airbnb": "^2.2.3",
        "babel-tape-runner": "^2.0.1",
        "editorconfig-tools": "^0.1.1",
        "eslint": "^3.15.0",
        "eslint-find-rules": "^1.14.3",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.9.0",
        "in-publish": "^2.0.0",
        "react": ">= 0.13.0",
        "safe-publish-latest": "^1.1.1",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "355d290040bbf8e00bf8b4b19f4b70cbe7c2317f",
        "tarball": "https://registry.npmjs.org/eslint-config-airbnb/-/eslint-config-airbnb-14.1.0.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "homepage": "https://github.com/airbnb/javascript",
    "keywords": [
        "eslint",
        "eslintconfig",
        "config",
        "airbnb",
        "javascript",
        "styleguide"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "airbnb"
        },
        {
            "name": "jitl"
        },
        {
            "name": "ljharb"
        }
    ],
    "name": "eslint-config-airbnb",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "^3.15.0",
        "eslint-plugin-jsx-a11y": "^3.0.2 || ^4.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-react": "^6.9.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/airbnb/javascript.git"
    },
    "scripts": {
        "lint": "eslint .",
        "prelint": "editorconfig-tools check * rules/* test/*",
        "prepublish": "(not-in-publish || npm test) && safe-publish-latest",
        "pretest": "npm run --silent lint",
        "test": "npm run --silent tests-only",
        "tests-only": "babel-tape-runner ./test/test-*.js",
        "travis": "cd ../eslint-config-airbnb-base && npm install && npm link && cd - && npm link eslint-config-airbnb-base && npm run --silent test ; npm unlink eslint-config-airbnb-base >/dev/null &"
    },
    "version": "14.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
