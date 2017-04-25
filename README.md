# npmtest-nodebb

#### basic test coverage for  [nodebb (v1.4.0)](http://www.nodebb.org)  [![npm package](https://img.shields.io/npm/v/npmtest-nodebb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nodebb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nodebb.svg)](https://travis-ci.org/npmtest/node-npmtest-nodebb)

#### NodeBB Forum

[![NPM](https://nodei.co/npm/nodebb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodebb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nodebb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodebb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nodebb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nodebb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nodebb/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nodebb/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nodebb/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nodebb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nodebb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nodebb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nodebb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodebb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nodebb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nodebb/build/test-report.html](https://npmtest.github.io/node-npmtest-nodebb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nodebb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nodebb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nodebb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodebb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodebb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodebb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nodebb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nodebb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/NodeBB/NodeBB/issues"
    },
    "dependencies": {
        "async": "~1.5.0",
        "autoprefixer": "^6.2.3",
        "bcryptjs": "~2.3.0",
        "body-parser": "^1.9.0",
        "chart.js": "^2.1.0",
        "colors": "^1.1.0",
        "compression": "^1.1.0",
        "connect-ensure-login": "^0.1.1",
        "connect-flash": "^0.1.1",
        "connect-mongo": "1.3.2",
        "connect-multiparty": "^2.0.0",
        "connect-redis": "~3.1.0",
        "cookie-parser": "^1.3.3",
        "cron": "^1.0.5",
        "csurf": "^1.6.1",
        "daemon": "~1.1.0",
        "express": "^4.14.0",
        "express-session": "^1.8.2",
        "express-useragent": "1.0.4",
        "html-to-text": "2.1.3",
        "ip": "1.1.3",
        "jimp": "0.2.27",
        "jquery": "^3.1.0",
        "json-2-csv": "^2.0.22",
        "less": "^2.0.0",
        "logrotate-stream": "^0.2.3",
        "lru-cache": "4.0.1",
        "mime": "^1.3.4",
        "minimist": "^1.1.1",
        "mkdirp": "~0.5.0",
        "mongodb": "2.2.10",
        "morgan": "^1.3.2",
        "mousetrap": "^1.5.3",
        "nconf": "~0.8.2",
        "nodebb-plugin-composer-default": "4.3.0",
        "nodebb-plugin-dbsearch": "1.0.4",
        "nodebb-plugin-emoji-extended": "1.1.1",
        "nodebb-plugin-emoji-one": "1.1.5",
        "nodebb-plugin-markdown": "7.0.1",
        "nodebb-plugin-mentions": "1.1.3",
        "nodebb-plugin-soundpack-default": "0.1.6",
        "nodebb-plugin-spam-be-gone": "0.4.10",
        "nodebb-rewards-essentials": "0.0.9",
        "nodebb-theme-lavender": "3.0.15",
        "nodebb-theme-persona": "4.1.88",
        "nodebb-theme-vanilla": "5.1.56",
        "nodebb-widget-essentials": "2.0.13",
        "nodemailer": "2.6.4",
        "nodemailer-sendmail-transport": "1.0.0",
        "nodemailer-smtp-transport": "^2.4.1",
        "passport": "^0.3.0",
        "passport-local": "1.0.0",
        "postcss": "^5.0.13",
        "postcss-clean": "^1.0.0",
        "promise-polyfill": "^6.0.2",
        "prompt": "^1.0.0",
        "redis": "~2.6.2",
        "request": "^2.44.0",
        "rimraf": "~2.5.0",
        "rss": "^1.0.0",
        "semver": "^5.1.0",
        "serve-favicon": "^2.1.5",
        "sitemap": "^1.4.0",
        "socket.io": "1.7.1",
        "socket.io-client": "1.7.1",
        "socket.io-redis": "2.0.0",
        "socketio-wildcard": "~0.3.0",
        "string": "^3.0.0",
        "templates.js": "0.3.4",
        "toobusy-js": "^0.5.1",
        "uglify-js": "^2.6.0",
        "underscore": "^1.8.3",
        "underscore.deep": "^0.5.1",
        "validator": "^6.1.0",
        "winston": "^2.1.0",
        "xregexp": "~3.1.0"
    },
    "description": "NodeBB Forum",
    "devDependencies": {
        "coveralls": "^2.11.14",
        "eslint": "^3.7.1",
        "eslint-config-airbnb": "^12.0.0",
        "eslint-plugin-import": "^1.16.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^6.4.1",
        "grunt": "~0.4.5",
        "grunt-contrib-watch": "^1.0.0",
        "istanbul": "^0.4.2",
        "mocha": "~3.1.0",
        "mocha-lcov-reporter": "^1.2.0",
        "xmlhttprequest": "1.8.0",
        "xmlhttprequest-ssl": "1.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "1fe9693bad16b1c441b490c03e2c6a35cd5cb474",
        "tarball": "https://registry.npmjs.org/nodebb/-/nodebb-1.4.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "d120ee86cfe2a55efcd3982cc3e8fa3f71284602",
    "homepage": "http://www.nodebb.org",
    "license": "GPL-3.0",
    "main": "app.js",
    "maintainers": [
        {
            "name": "alebcay"
        },
        {
            "name": "julianlam"
        },
        {
            "name": "baris"
        },
        {
            "name": "psychobunny"
        }
    ],
    "name": "nodebb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "https://github.com/NodeBB/NodeBB/"
    },
    "scripts": {
        "coveralls": "istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "lint": "eslint --cache .",
        "pretest": "npm run lint",
        "start": "node loader.js",
        "test": "istanbul cover _mocha test",
        "test-windows": "_mocha test"
    },
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
