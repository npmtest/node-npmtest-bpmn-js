# test coverage for  [bpmn-js (v0.20.5)](https://github.com/bpmn-io/bpmn-js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bpmn-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bpmn-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bpmn-js.svg)](https://travis-ci.org/npmtest/node-npmtest-bpmn-js)
#### A bpmn 2.0 toolkit and web modeler

[![NPM](https://nodei.co/npm/bpmn-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bpmn-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bpmn-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bpmn-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bpmn-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bpmn-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bpmn-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bpmn-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bpmn-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bpmn-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bpmn-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bpmn-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bpmn-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bpmn-js/build/test-report.html](https://npmtest.github.io/node-npmtest-bpmn-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bpmn-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bpmn-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bpmn-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bpmn-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bpmn-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bpmn-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bpmn-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bpmn-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nico Rehwaldt",
        "url": "https://github.com/nikku"
    },
    "bugs": {
        "url": "https://github.com/bpmn-io/bpmn-js/issues"
    },
    "contributors": [
        {
            "name": "bpmn.io contributors",
            "url": "https://github.com/bpmn-io"
        }
    ],
    "dependencies": {
        "bpmn-moddle": "^0.14.0",
        "diagram-js": "^0.19.3",
        "diagram-js-direct-editing": "^0.17.1",
        "diagram-js-origin": "^0.15.1",
        "ids": "^0.2.0",
        "inherits": "^2.0.1",
        "lodash": "^3.0.1",
        "min-dom": "^0.2.0",
        "object-refs": "^0.1.1",
        "tiny-svg": "^0.1.1"
    },
    "description": "A bpmn 2.0 toolkit and web modeler",
    "devDependencies": {
        "browserify": "^13.0.0",
        "browserify-derequire": "^0.9.1",
        "bundle-collapser": "^1.1.1",
        "chai": "~2.2.0",
        "eslint": "^2.11.1",
        "eslint-plugin-mocha": "^2.2.0",
        "grunt": "^0.4.4",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-copy": "^0.7.0",
        "grunt-eslint": "^18.1.0",
        "grunt-karma": "^0.12.0",
        "grunt-release": "^0.7.0",
        "jsondiffpatch": "^0.1.26",
        "karma": "^0.13.0",
        "karma-browserify": "^5.0.1",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^0.2.2",
        "karma-env-preprocessor": "^0.1.1",
        "karma-firefox-launcher": "^0.1.3",
        "karma-ie-launcher": "^0.2.0",
        "karma-mocha": "~0.1.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-safari-launcher": "^0.1.1",
        "karma-sinon-chai": "~0.3.0",
        "karma-spec-reporter": "0.0.26",
        "load-grunt-tasks": "^0.3.0",
        "mocha": "^2.2.5",
        "mocha-test-container-support": "0.2.0",
        "phantomjs-prebuilt": "^2.1.12",
        "sinon": "~1.14.1",
        "sinon-chai": "~2.7.0",
        "source-map-concat": "^1.0.0",
        "stringify": "^3.1.0",
        "time-grunt": "^0.3.2",
        "uglify-js": "^2.4.16",
        "watchify": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4a7f8e8809cc88ad80d0635663902475b7fe73eb",
        "tarball": "https://registry.npmjs.org/bpmn-js/-/bpmn-js-0.20.5.tgz"
    },
    "gitHead": "8e64fc3a8b630d8d57da420ba85ab0ee9d831d9a",
    "homepage": "https://github.com/bpmn-io/bpmn-js#readme",
    "keywords": [
        "bpmn",
        "bpmn-js",
        "toolkit",
        "web modeler",
        "modeler",
        "modeling",
        "process modeling"
    ],
    "license": "SEE LICENSE IN LICENSE",
    "maintainers": [
        {
            "name": "nikku"
        },
        {
            "name": "iso50"
        },
        {
            "name": "bpmn-io"
        },
        {
            "name": "ricardomatias"
        }
    ],
    "name": "bpmn-js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bpmn-io/bpmn-js.git"
    },
    "scripts": {
        "all": "grunt",
        "dev": "grunt auto-test",
        "distro": "grunt build",
        "lint": "grunt lint",
        "test": "grunt test"
    },
    "version": "0.20.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
