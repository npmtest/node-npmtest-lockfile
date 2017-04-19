# npmtest-lockfile

#### test coverage for  [lockfile (v1.0.3)](https://github.com/npm/lockfile#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-lockfile.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lockfile) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lockfile.svg)](https://travis-ci.org/npmtest/node-npmtest-lockfile)

#### A very polite lock file utility, which endeavors to not litter, and to wait patiently for others.

[![NPM](https://nodei.co/npm/lockfile.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lockfile)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lockfile/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lockfile/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lockfile/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lockfile/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lockfile/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lockfile/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lockfile/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lockfile/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lockfile/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lockfile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lockfile/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lockfile/build/test-report.html](https://npmtest.github.io/node-npmtest-lockfile/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lockfile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lockfile/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lockfile/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lockfile/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lockfile/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lockfile/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lockfile/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lockfile/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "url": "http://blog.izs.me/"
    },
    "bugs": {
        "url": "https://github.com/npm/lockfile/issues"
    },
    "dependencies": {},
    "description": "A very polite lock file utility, which endeavors to not litter, and to wait patiently for others.",
    "devDependencies": {
        "tap": "^7.1.2",
        "touch": "0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "2638fc39a0331e9cac1a04b71799931c9c50df79",
        "tarball": "https://registry.npmjs.org/lockfile/-/lockfile-1.0.3.tgz"
    },
    "gitHead": "96549505fcca4b8b0ff0e833719720bd463306d7",
    "homepage": "https://github.com/npm/lockfile#readme",
    "keywords": [
        "lockfile",
        "lock",
        "file",
        "fs",
        "O_EXCL"
    ],
    "license": "ISC",
    "main": "lockfile.js",
    "maintainers": [
        {
            "name": "trevorburnham"
        },
        {
            "name": "isaacs"
        }
    ],
    "name": "lockfile",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/npm/lockfile.git"
    },
    "scripts": {
        "changelog": "bash gen-changelog.sh",
        "postversion": "npm run changelog && git add CHANGELOG.md && git commit -m 'update changelog - '${npm_package_version}",
        "test": "tap test/*.js --cov"
    },
    "version": "1.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
