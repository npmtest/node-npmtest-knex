# npmtest-knex

#### basic test coverage for  [knex (v0.12.9)](https://github.com/tgriesser/knex#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-knex.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-knex) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-knex.svg)](https://travis-ci.org/npmtest/node-npmtest-knex)

#### A batteries-included SQL query & schema builder for Postgres, MySQL and SQLite3 and the Browser

[![NPM](https://nodei.co/npm/knex.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/knex)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-knex/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-knex/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-knex/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-knex/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-knex/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-knex/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-knex/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-knex/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-knex/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-knex/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-knex/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-knex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-knex/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-knex/build/test-report.html](https://npmtest.github.io/node-npmtest-knex/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-knex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-knex/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-knex/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-knex/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-knex/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-knex/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-knex/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-knex/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Griesser",
        "url": "https://github.com/tgriesser"
    },
    "bin": {
        "knex": "./bin/cli.js"
    },
    "browser": {
        "./lib/migrate/index.js": "./lib/util/noop.js",
        "./lib/bin/cli.js": "./lib/util/noop.js",
        "./lib/seed/index.js": "./lib/util/noop.js",
        "mssql": false,
        "mysql": false,
        "mysql2": false,
        "mariasql": false,
        "pg": false,
        "pg-query-stream": false,
        "oracle": false,
        "strong-oracle": false,
        "sqlite3": false,
        "oracledb": false
    },
    "bugs": {
        "url": "https://github.com/tgriesser/knex/issues"
    },
    "buildDependencies": [
        "babel-cli",
        "babel-plugin-add-module-exports",
        "babel-plugin-lodash",
        "babel-plugin-transform-runtime",
        "babel-preset-es2015",
        "babel-preset-es2015-loose",
        "rimraf"
    ],
    "dependencies": {
        "babel-runtime": "^6.11.6",
        "bluebird": "^3.4.6",
        "chalk": "^1.0.0",
        "commander": "^2.2.0",
        "debug": "^2.1.3",
        "generic-pool": "^2.4.2",
        "inherits": "~2.0.1",
        "interpret": "^0.6.5",
        "liftoff": "~2.2.0",
        "lodash": "^4.6.0",
        "minimist": "~1.1.0",
        "mkdirp": "^0.5.0",
        "pg-connection-string": "^0.1.3",
        "readable-stream": "^1.1.12",
        "safe-buffer": "^5.0.1",
        "tildify": "~1.0.0",
        "uuid": "^3.0.0",
        "v8flags": "^2.0.2"
    },
    "description": "A batteries-included SQL query & schema builder for Postgres, MySQL and SQLite3 and the Browser",
    "devDependencies": {
        "JSONStream": "^1.0.3",
        "async": "^0.9.0",
        "babel-cli": "^6.11.4",
        "babel-eslint": "^5.0.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-lodash": "3.2.9",
        "babel-plugin-transform-runtime": "^6.12.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-es2015-loose": "^8.0.0",
        "chai": "^3.5.0",
        "coveralls": "~2.11.1",
        "eslint": "2.2.0",
        "eslint-plugin-import": "^1.8.0",
        "istanbul": "^0.4.5",
        "json-loader": "^0.5.4",
        "mariasql": "^0.2.3",
        "mocha": "^3.1.2",
        "mysql": "^2.6.2",
        "mysql2": "^1.1.1",
        "pg": "^6.1.0",
        "pg-query-stream": "^1.0.0",
        "rimraf": "2.x",
        "sinon": "^1.10.0",
        "sinon-chai": "^2.5.0",
        "source-map-support": "^0.4.0",
        "sqlite3": "^3.0.5",
        "tap-spec": "^4.0.0",
        "tape": "^4.0.0",
        "through": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "aa852138c09ed46181e890fd698270bbe7761124",
        "tarball": "https://registry.npmjs.org/knex/-/knex-0.12.9.tgz"
    },
    "files": [
        "CONTRIBUTING.md",
        "README.md",
        "bin/*",
        "src/*",
        "lib/*",
        "knex.js",
        "LICENSE",
        "CHANGELOG.md",
        "scripts/*"
    ],
    "gitHead": "ce375c54230297e7cd20964b63a1c214e57693db",
    "homepage": "https://github.com/tgriesser/knex#readme",
    "keywords": [
        "sql",
        "query",
        "postgresql",
        "mysql",
        "mariadb",
        "sqlite3",
        "oracle",
        "mssql"
    ],
    "license": "MIT",
    "main": "knex.js",
    "maintainers": [
        {
            "name": "elhigu"
        },
        {
            "name": "erisds"
        },
        {
            "name": "kirrg001"
        },
        {
            "name": "rhys-vdw"
        },
        {
            "name": "tgriesser"
        },
        {
            "name": "tjwebb"
        },
        {
            "name": "tkellen"
        },
        {
            "name": "wubzz"
        }
    ],
    "name": "knex",
    "optionalDependencies": {},
    "react-native": {
        "./lib/migrate": "./lib/util/noop.js",
        "./lib/seed": "./lib/util/noop.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/tgriesser/knex.git"
    },
    "scripts": {
        "babel": "rimraf ./lib && babel src --out-dir lib --copy-files",
        "build": "npm run babel",
        "coveralls": "cat ./test/coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "debug_tape": "node-debug test/tape/index.js",
        "debug_test": "node-debug _mocha -t 0 test/index.js",
        "dev": "rm -rf ./lib && babel -w src --out-dir lib --copy-files",
        "lint": "eslint src/**",
        "plaintest": "mocha --check-leaks -b -R spec test/index.js && npm run tape",
        "prepublish": "npm run babel",
        "tape": "node test/tape/index.js | tap-spec",
        "test": "npm run lint && istanbul --config=test/.istanbul.yml cover node_modules/mocha/bin/_mocha -- --check-leaks -t 10000 -b -R spec test/index.js && npm run tape"
    },
    "version": "0.12.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
