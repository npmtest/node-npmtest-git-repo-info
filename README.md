# test coverage for  [git-repo-info (v1.4.1)](https://github.com/rwjblue/git-repo-info)  [![npm package](https://img.shields.io/npm/v/npmtest-git-repo-info.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-git-repo-info) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-git-repo-info.svg)](https://travis-ci.org/npmtest/node-npmtest-git-repo-info)
#### Retrieve current sha and branch name from a git repo.

[![NPM](https://nodei.co/npm/git-repo-info.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/git-repo-info)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-git-repo-info/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-git-repo-info/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-git-repo-info/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-git-repo-info/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-git-repo-info/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-git-repo-info/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-git-repo-info/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-git-repo-info/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-git-repo-info/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-git-repo-info/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-git-repo-info/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-git-repo-info/build/test-report.html](https://npmtest.github.io/node-npmtest-git-repo-info/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-git-repo-info/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-git-repo-info/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-git-repo-info/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-git-repo-info/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-git-repo-info/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-git-repo-info/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-git-repo-info/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-git-repo-info/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Robert Jackson"
    },
    "bugs": {
        "url": "https://github.com/rwjblue/git-repo-info/issues"
    },
    "dependencies": {},
    "description": "Retrieve current sha and branch name from a git repo.",
    "devDependencies": {
        "mocha": "^1.21.4",
        "mocha-jshint": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2a072823254aaf62fcf0766007d7b6651bd41943",
        "tarball": "https://registry.npmjs.org/git-repo-info/-/git-repo-info-1.4.1.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "3f25daa29dcfeb3146de4ec80eb2275ebd66d21f",
    "homepage": "https://github.com/rwjblue/git-repo-info",
    "keywords": [
        "git"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rwjblue"
        }
    ],
    "name": "git-repo-info",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rwjblue/git-repo-info.git"
    },
    "scripts": {
        "postversion": "git push && git push --tags && npm publish",
        "preversion": "npm test",
        "test": "mocha tests"
    },
    "version": "1.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
