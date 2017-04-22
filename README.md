# npmtest-rename

#### basic test coverage for  [rename (v1.0.4)](https://github.com/popomore/rename)  [![npm package](https://img.shields.io/npm/v/npmtest-rename.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rename) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rename.svg)](https://travis-ci.org/npmtest/node-npmtest-rename)

#### Rename files using some transformers.

[![NPM](https://nodei.co/npm/rename.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rename)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rename/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rename/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rename/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rename/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rename/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rename/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rename/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rename/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rename/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rename/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rename/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rename/build/test-report.html](https://npmtest.github.io/node-npmtest-rename/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rename/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rename/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rename/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rename/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rename/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rename/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rename/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rename/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "popomore"
    },
    "bugs": {
        "url": "https://github.com/popomore/rename/issues"
    },
    "ci": {
        "version": "4, 6, 7"
    },
    "dependencies": {
        "debug": "^2.5.2"
    },
    "description": "Rename files using some transformers.",
    "devDependencies": {
        "autod": "^2.7.1",
        "egg-bin": "^1.9.1",
        "egg-ci": "^1.1.0",
        "eslint": "^3.12.2",
        "eslint-config-egg": "^3.2.0",
        "should": "^11.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "a0f25078fa4195e650f73050c7c12ccf689f430b",
        "tarball": "https://registry.npmjs.org/rename/-/rename-1.0.4.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "ddf65979f88217efb648e92145550d9b3025d23a",
    "homepage": "https://github.com/popomore/rename",
    "keywards": [
        "rename",
        "file",
        "path",
        "transform"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "hgpa"
        },
        {
            "name": "hparra"
        },
        {
            "name": "popomore"
        }
    ],
    "name": "rename",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/popomore/rename.git"
    },
    "scripts": {
        "autod": "autod",
        "ci": "npm run lint && egg-bin cov",
        "cov": "egg-bin cov",
        "lint": "eslint index.js lib test",
        "test": "npm run lint && egg-bin test"
    },
    "version": "1.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
