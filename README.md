# npmtest-devtool

#### basic test coverage for  [devtool (v2.3.1)](https://github.com/Jam3/devtool)  [![npm package](https://img.shields.io/npm/v/npmtest-devtool.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-devtool) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-devtool.svg)](https://travis-ci.org/npmtest/node-npmtest-devtool)

#### runs Node.js programs through Chromium DevTools

[![NPM](https://nodei.co/npm/devtool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/devtool)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-devtool/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-devtool/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-devtool/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-devtool/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-devtool/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-devtool/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-devtool/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-devtool/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-devtool/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-devtool/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-devtool/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-devtool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-devtool/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-devtool/build/test-report.html](https://npmtest.github.io/node-npmtest-devtool/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-devtool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-devtool/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-devtool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-devtool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-devtool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-devtool/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-devtool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-devtool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt DesLauriers",
        "url": "https://github.com/mattdesl"
    },
    "bin": {
        "devtool": "./bin/index.js"
    },
    "bugs": {
        "url": "https://github.com/Jam3/devtool/issues"
    },
    "dependencies": {
        "browser-resolve": "^1.11.0",
        "chokidar": "^1.4.2",
        "combine-source-map": "^0.7.1",
        "concat-stream": "^1.5.1",
        "convert-source-map": "^1.2.0",
        "deep-extend": "^0.4.1",
        "electron": "1.4.15",
        "events": "^1.1.0",
        "mime": "^1.3.4",
        "minimist": "^1.2.0",
        "mock-stdin": "^0.3.0",
        "object-assign": "^4.0.1",
        "rc": "^1.1.6",
        "resolve": "^1.1.7",
        "serializerr": "^1.0.2",
        "sliced": "^1.0.1",
        "strip-bom": "^2.0.0",
        "syntax-error": "^1.1.4",
        "through2": "^2.0.0"
    },
    "description": "runs Node.js programs through Chromium DevTools",
    "devDependencies": {
        "awesome-streetview": "^1.4.2",
        "babel-plugin-transform-es2015-template-literals": "^6.3.13",
        "babel-register": "^6.11.6",
        "bluebird": "^3.1.5",
        "browserify": "^13.0.0",
        "concat-stream": "^1.5.1",
        "cross-spawn-async": "^2.1.6",
        "electron-canvas-to-buffer": "^1.0.3",
        "faucet": "0.0.1",
        "get-stdin": "^5.0.1",
        "github-markdown-css": "^2.2.0",
        "google-panorama-by-location": "^4.1.1",
        "google-panorama-equirectangular": "^1.2.0",
        "insert-css": "^0.2.0",
        "marked": "^0.3.5",
        "semistandard": "^7.0.5",
        "tape": "^4.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "eb259ff04c81a218d9163334fe29b024a24e8855",
        "tarball": "https://registry.npmjs.org/devtool/-/devtool-2.3.1.tgz"
    },
    "gitHead": "4f46fd4accc97b8e1490ab5302c1a4a1d18bd54a",
    "homepage": "https://github.com/Jam3/devtool",
    "keywords": [],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mattdesl"
        }
    ],
    "name": "devtool",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Jam3/devtool.git"
    },
    "scripts": {
        "example:browserify": "./bin/index.js example/browserify.js",
        "example:es2015": "./bin/index.js example/es2015.js -w -i example/es2015.html",
        "example:geolocate": "./bin/index.js example/geolocate.js -qch",
        "example:http": "./bin/index.js example/http -w --break",
        "example:markdown": "./bin/index.js example/markdown.js -qch < README.md > example/markdown.png",
        "example:streetview": "./bin/index.js example/streetview.js -h -i example/streetview.html -q --bf > example/streetview.png",
        "example:tape-browser": "browserify example/tape-browser.js | ./bin/index.js -c -t 1000 | faucet",
        "lint": "semistandard",
        "start": "node server.js",
        "test": "npm run lint && node test/index.js | faucet"
    },
    "semistandard": {
        "ignore": [
            "test/fixtures/*.js"
        ]
    },
    "version": "2.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
