# test coverage for  [public-ip (v2.3.3)](https://github.com/sindresorhus/public-ip#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-public-ip.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-public-ip) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-public-ip.svg)](https://travis-ci.org/npmtest/node-npmtest-public-ip)
#### Get your public IP address - very fast!

[![NPM](https://nodei.co/npm/public-ip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/public-ip)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-public-ip/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-public-ip/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-public-ip/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-public-ip/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-public-ip/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-public-ip/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-public-ip/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-public-ip/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-public-ip/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-public-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-public-ip/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-public-ip/build/test-report.html](https://npmtest.github.io/node-npmtest-public-ip/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-public-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-public-ip/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-public-ip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-public-ip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-public-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-public-ip/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-public-ip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-public-ip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "browser": "browser.js",
    "bugs": {
        "url": "https://github.com/sindresorhus/public-ip/issues"
    },
    "dependencies": {
        "dns-socket": "^1.6.1",
        "got": "^6.7.1",
        "is-ip": "^2.0.0",
        "pify": "^2.3.0"
    },
    "description": "Get your public IP address - very fast!",
    "devDependencies": {
        "ava": "*",
        "is-ip": "^2.0.0",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "728f1039a1c441e659ee96bab6baa80b1fbda477",
        "tarball": "https://registry.npmjs.org/public-ip/-/public-ip-2.3.3.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "browser.js"
    ],
    "gitHead": "c6c6c85e01646bf535517a683458d475d280fe6b",
    "homepage": "https://github.com/sindresorhus/public-ip#readme",
    "keywords": [
        "get",
        "ip",
        "ipv4",
        "ipv6",
        "address",
        "external",
        "public",
        "machine",
        "fast",
        "opendns",
        "dns"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "silverwind"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "public-ip",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/public-ip.git"
    },
    "scripts": {
        "test": "xo && ava test.js"
    },
    "version": "2.3.3",
    "xo": {
        "envs": [
            "node",
            "browser"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
