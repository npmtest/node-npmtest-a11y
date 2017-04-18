# npmtest-a11y

#### test coverage for  [a11y (v0.5.0)](https://github.com/addyosmani/a11y#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-a11y.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-a11y) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-a11y.svg)](https://travis-ci.org/npmtest/node-npmtest-a11y)

#### Runs an accessibility audit against a URL

[![NPM](https://nodei.co/npm/a11y.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/a11y)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-a11y/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-a11y/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-a11y/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-a11y/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-a11y/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-a11y/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-a11y/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-a11y/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-a11y/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-a11y/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-a11y/build/test-report.html](https://npmtest.github.io/node-npmtest-a11y/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-a11y/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-a11y/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-a11y/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-a11y/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-a11y/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-a11y/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "a11y": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/addyosmani/a11y/issues"
    },
    "dependencies": {
        "accessibility-developer-tools": "^2.6.0",
        "chalk": "^1.0.0",
        "each-async": "^1.1.0",
        "globby": "^6.1.0",
        "humanize-url": "^1.0.0",
        "indent-string": "^3.1.0",
        "log-symbols": "^1.0.1",
        "meow": "^3.3.0",
        "parse-json": "^2.1.0",
        "phantomjs-polyfill": "0.0.2",
        "phantomjs-prebuilt": "^2.1.12",
        "protocolify": "^2.0.0",
        "update-notifier": "^2.0.0"
    },
    "description": "Runs an accessibility audit against a URL",
    "devDependencies": {
        "ava": "^0.18.0",
        "xo": "^0.17.0"
    },
    "directories": {},
    "dist": {
        "shasum": "450320380094baa64093b953f3937239c150fd68",
        "tarball": "https://registry.npmjs.org/a11y/-/a11y-0.5.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "cli.js",
        "audits.js"
    ],
    "gitHead": "1d13eef6c0abd60ce896b87b897f7b008922a4b3",
    "homepage": "https://github.com/addyosmani/a11y#readme",
    "keywords": [
        "cli-app",
        "cli",
        "a11y",
        "audit",
        "test",
        "accessibility",
        "wai",
        "aria",
        "dev",
        "developer",
        "tool",
        "report",
        "web",
        "website"
    ],
    "license": "Apache-2.0",
    "maintainers": [
        {
            "name": "addyosmani"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "a11y",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/addyosmani/a11y.git"
    },
    "scripts": {
        "demo": "./cli.js theverge.com",
        "test": "xo && ava test/test.js"
    },
    "version": "0.5.0",
    "xo": {
        "space": 4,
        "ignores": [
            "audits.js"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
