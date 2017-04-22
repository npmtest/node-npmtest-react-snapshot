# npmtest-react-snapshot

#### basic test coverage for  [react-snapshot (v1.0.4)](https://github.com/geelen/react-snapshot)  [![npm package](https://img.shields.io/npm/v/npmtest-react-snapshot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-snapshot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-snapshot.svg)](https://travis-ci.org/npmtest/node-npmtest-react-snapshot)

#### A zero-configuration static pre-renderer for React apps. Starting by targetting Create React App (because it's great)

[![NPM](https://nodei.co/npm/react-snapshot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-snapshot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-snapshot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-snapshot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-snapshot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-snapshot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-snapshot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-snapshot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-snapshot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-snapshot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-snapshot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-snapshot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-snapshot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-snapshot/build/test-report.html](https://npmtest.github.io/node-npmtest-react-snapshot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-snapshot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-snapshot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-snapshot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-snapshot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-snapshot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-snapshot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-snapshot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-snapshot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Glen Maddern"
    },
    "babel": {
        "presets": [
            "es2015",
            "es2016"
        ],
        "plugins": [
            "add-module-exports"
        ]
    },
    "bin": {
        "react-snapshot": "./bin/react-snapshot.js"
    },
    "dependencies": {
        "jsdom": "^9.4.5",
        "mkdirp": "^0.5.1",
        "pushstate-server": "^1.12.0",
        "react": "^15.3.0",
        "react-dom": "^15.3.0"
    },
    "description": "A zero-configuration static pre-renderer for React apps. Starting by targetting Create React App (because it's great)",
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-core": "^6.13.2",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-es2016": "^6.11.3"
    },
    "directories": {},
    "dist": {
        "shasum": "57cf3e756cf02c1031f295e135e0819c5bc38dcb",
        "tarball": "https://registry.npmjs.org/react-snapshot/-/react-snapshot-1.0.4.tgz"
    },
    "gitHead": "5c6ec05a10547d5c7b14ce955169616288c97635",
    "homepage": "https://github.com/geelen/react-snapshot",
    "keywords": [
        "react",
        "create-react-app",
        "snapshot",
        "static-site-generator",
        "jsdom"
    ],
    "license": "ISC",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "geelen"
        }
    ],
    "name": "react-snapshot",
    "optionalDependencies": {},
    "scripts": {
        "build": "babel --out-dir lib src",
        "build:watch": "npm run build -- --watch",
        "prepublish": "rm -rf lib/* && npm run build"
    },
    "version": "1.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
