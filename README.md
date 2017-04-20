# npmtest-babel-preset-react-hmre

#### basic test coverage for  [babel-preset-react-hmre (v1.1.1)](https://github.com/danmartinez101/babel-preset-react-hmre)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-preset-react-hmre.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-preset-react-hmre) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-preset-react-hmre.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-preset-react-hmre)

#### Babel preset for React HMR and Error Catching

[![NPM](https://nodei.co/npm/babel-preset-react-hmre.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-preset-react-hmre)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-preset-react-hmre/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-preset-react-hmre/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-preset-react-hmre/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-preset-react-hmre/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-preset-react-hmre/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-preset-react-hmre/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-preset-react-hmre/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Martinez"
    },
    "bugs": {
        "url": "https://github.com/danmartinez101/babel-preset-react-hmre/issues"
    },
    "dependencies": {
        "babel-plugin-react-transform": "^2.0.2",
        "react-transform-catch-errors": "^1.0.2",
        "react-transform-hmr": "^1.0.3",
        "redbox-react": "^1.2.2"
    },
    "description": "Babel preset for React HMR and Error Catching",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-preset-react": "^6.3.13",
        "react": "^0.14.7"
    },
    "directories": {},
    "dist": {
        "shasum": "d216e60cb5b8d4c873e19ed0f54eaff1437bc492",
        "tarball": "https://registry.npmjs.org/babel-preset-react-hmre/-/babel-preset-react-hmre-1.1.1.tgz"
    },
    "gitHead": "4ff32ed3ec39c9d003ce125543a678311b1f8d7d",
    "homepage": "https://github.com/danmartinez101/babel-preset-react-hmre",
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "danmartinez101"
        },
        {
            "name": "gaearon"
        }
    ],
    "name": "babel-preset-react-hmre",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danmartinez101/babel-preset-react-hmre.git"
    },
    "scripts": {
        "test": "babel --presets react,../index test/ | grep \"_wrapComponent('Test')(class Test extends React.Component {\""
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
