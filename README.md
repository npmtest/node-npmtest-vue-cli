# npmtest-vue-cli

#### test coverage for  [vue-cli (v2.8.1)](https://github.com/vuejs/vue-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-vue-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vue-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vue-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-vue-cli)

#### A simple CLI for scaffolding Vue.js projects.

[![NPM](https://nodei.co/npm/vue-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vue-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vue-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vue-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vue-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vue-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vue-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vue-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vue-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vue-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vue-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-vue-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vue-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vue-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vue-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vue-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vue-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vue-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vue-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vue-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan You"
    },
    "bin": {
        "vue": "bin/vue",
        "vue-init": "bin/vue-init",
        "vue-list": "bin/vue-list",
        "vue-build": "bin/vue-build"
    },
    "bugs": {
        "url": "https://github.com/vuejs/vue-cli/issues"
    },
    "dependencies": {
        "async": "^2.0.0-rc.2",
        "autoprefixer": "^6.6.1",
        "babel-core": "^6.21.0",
        "babel-loader": "^6.2.10",
        "babel-preset-vue-app": "^0.4.0",
        "chalk": "^1.1.1",
        "commander": "^2.9.0",
        "connect-history-api-fallback": "^1.3.0",
        "consolidate": "^0.14.0",
        "css-loader": "^0.26.1",
        "download-git-repo": "^0.2.1",
        "express": "^4.14.0",
        "extract-text-webpack-plugin": "2.0.0-beta.5",
        "file-loader": "^0.9.0",
        "friendly-errors-webpack-plugin": "^1.1.2",
        "handlebars": "^4.0.5",
        "html-webpack-plugin": "^2.26.0",
        "http-proxy-middleware": "^0.17.3",
        "inquirer": "^0.12.0",
        "installed-by-yarn-globally": "^0.1.1",
        "metalsmith": "^2.1.0",
        "minimatch": "^3.0.0",
        "multimatch": "^2.1.0",
        "opn": "^4.0.2",
        "ora": "^0.2.1",
        "post-compile-webpack-plugin": "^0.1.0",
        "postcss-loader": "^1.2.1",
        "read-metadata": "^1.0.0",
        "request": "^2.67.0",
        "rimraf": "^2.5.0",
        "semver": "^5.1.0",
        "tildify": "^1.2.0",
        "url-loader": "^0.5.7",
        "user-home": "^2.0.0",
        "validate-npm-package-name": "^2.2.2",
        "vue": "^2.1.10",
        "vue-loader": "^10.0.2",
        "vue-template-compiler": "^2.1.10",
        "webpack": "^2.2.0",
        "webpack-dev-middleware": "^1.9.0",
        "webpack-hot-middleware": "^2.15.0",
        "webpack-merge": "^2.3.1"
    },
    "description": "A simple CLI for scaffolding Vue.js projects.",
    "devDependencies": {
        "chai": "^3.5.0",
        "cross-env": "^1.0.7",
        "eslint": "^2.7.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-standard": "^1.3.2",
        "execa": "^0.5.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "1f11147346c618a943580a6584b9b7cd55a1bd02",
        "tarball": "https://registry.npmjs.org/vue-cli/-/vue-cli-2.8.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "c75cb4643de206eea3cd66b62753d98c07500302",
    "homepage": "https://github.com/vuejs/vue-cli#readme",
    "keywords": [
        "vue",
        "cli",
        "spa"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "yyx990803"
        }
    ],
    "name": "vue-cli",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vuejs/vue-cli.git"
    },
    "scripts": {
        "e2e": "rimraf test/e2e/mock-template-build && cross-env BABEL_ENV=development mocha test/e2e/test.js --slow 1000 --compilers js:babel-core/register",
        "e2e:build": "cross-env BABEL_ENV=development mocha test/e2e/test-build.js --timeout 60000 --compilers js:babel-core/register",
        "lint": "eslint test/e2e/test*.js lib bin/* --env mocha",
        "test": "npm run lint && npm run e2e && npm run e2e:build"
    },
    "version": "2.8.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
