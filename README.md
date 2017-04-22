# npmtest-react-draggable

#### basic test coverage for  [react-draggable (v2.2.3)](https://github.com/mzabriskie/react-draggable)  [![npm package](https://img.shields.io/npm/v/npmtest-react-draggable.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-draggable) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-draggable.svg)](https://travis-ci.org/npmtest/node-npmtest-react-draggable)

#### React draggable component

[![NPM](https://nodei.co/npm/react-draggable.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-draggable)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-draggable/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-draggable/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-draggable/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-draggable/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-draggable/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-draggable/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-draggable/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-draggable/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-draggable/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-draggable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-draggable/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-draggable/build/test-report.html](https://npmtest.github.io/node-npmtest-react-draggable/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-draggable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-draggable/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-draggable/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-draggable/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-draggable/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-draggable/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-draggable/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-draggable/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-draggable",
    "version": "2.2.3",
    "description": "React draggable component",
    "main": "dist/react-draggable.js",
    "browser": "dist/react-draggable.js",
    "scripts": {
        "test": "make test",
        "test-debug": "karma start --browsers=Chrome",
        "test-ie": "karma start --browsers=IE",
        "dev": "make dev",
        "build": "make clean build",
        "lint": "make lint"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/mzabriskie/react-draggable.git"
    },
    "keywords": [
        "react",
        "draggable",
        "react-component"
    ],
    "author": "Matt Zabriskie",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mzabriskie/react-draggable/issues"
    },
    "homepage": "https://github.com/mzabriskie/react-draggable",
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-core": "^6.10.4",
        "babel-eslint": "^6.1.2",
        "babel-loader": "^6.2.4",
        "babel-plugin-espower": "^2.3.1",
        "babel-plugin-transform-flow-comments": "^6.8.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.11.1",
        "babel-preset-stage-1": "^6.5.0",
        "eslint": "^3.1.1",
        "eslint-plugin-react": "^5.2.2",
        "flow-bin": "^0.35.0",
        "jasmine-core": "^2.4.1",
        "json-loader": "^0.5.4",
        "karma": "^1.1.1",
        "karma-chrome-launcher": "^1.0.1",
        "karma-cli": "1.0.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-ie-launcher": "^1.0.0",
        "karma-jasmine": "^1.0.2",
        "karma-phantomjs-launcher": "^1.0.1",
        "karma-phantomjs-shim": "^1.4.0",
        "karma-webpack": "^1.7.0",
        "lodash": "^4.13.1",
        "open": "0.0.5",
        "phantomjs-prebuilt": ">=2.1",
        "power-assert": "^1.4.1",
        "pre-commit": "^1.1.3",
        "react": "^15.2.1",
        "react-addons-test-utils": "^15.4.0",
        "react-dom": "^15.2.1",
        "react-frame-component": "0.6.2",
        "semver": "^5.3.0",
        "static-server": "^2.0.3",
        "uglify-js": "^2.7.0",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1"
    },
    "precommit": [
        "lint",
        "test"
    ],
    "dependencies": {
        "classnames": "^2.2.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
