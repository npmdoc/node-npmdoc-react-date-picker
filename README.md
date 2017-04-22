# npmdoc-react-date-picker

#### api documentation for  [react-date-picker (v5.3.28)](https://github.com/zippyui/react-date-picker)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-date-picker.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-date-picker) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-date-picker.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-date-picker)

#### A carefully crafted date picker for React

[![NPM](https://nodei.co/npm/react-date-picker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-date-picker)

- [https://npmdoc.github.io/node-npmdoc-react-date-picker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-date-picker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-date-picker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-date-picker/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-date-picker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-date-picker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ZippyUI"
    },
    "bugs": {
        "url": "https://github.com/zippyui/react-date-picker/issues"
    },
    "contributors": [],
    "dependencies": {
        "lodash.throttle": "^4.0.1",
        "object-assign": "4.0.1",
        "raf": "3.2.0",
        "react-class": "2.0.0",
        "react-field": "2.0.2",
        "react-flex": "2.2.7",
        "react-inline-block": "2.0.0",
        "react-notify-resize": "1.0.3",
        "react-style-normalizer": "1.2.8"
    },
    "description": "A carefully crafted date picker for React",
    "devDependencies": {
        "autoprefixer-loader": "^3.2.0",
        "babel-cli": "^6.7.7",
        "babel-core": "^6.5.0",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-react": "^6.5.0",
        "css-loader": "^0.15.5",
        "eslint": "^2.10.2",
        "eslint-config-zippyui": "^1.0.1",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.8.4",
        "json-loader": "^0.5.2",
        "mocha": "^2.2.4",
        "node-libs-browser": "^0.5.2",
        "node-sass": "^3.5.3",
        "react": ">=0.14.0 || >=15.0.0",
        "react-dom": ">=0.14.0 || >=15.0.0",
        "react-hot-loader": "^1.2.8",
        "rimraf": "^2.5.2",
        "sass-loader": "^3.2.0",
        "should": "^6.0.3",
        "style-loader": "^0.13.1",
        "url-loader": "^0.5.6",
        "webpack": "^1.13.0",
        "webpack-dev-server": "^1.14.1",
        "zippyui-theme-builder": "^1.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "b7baeee261c5c8dcb909973fb9788914ef07f518",
        "tarball": "https://registry.npmjs.org/react-date-picker/-/react-date-picker-5.3.28.tgz"
    },
    "gitHead": "39ed16c61586cad37379e29ed938b838651fac91",
    "homepage": "https://github.com/zippyui/react-date-picker",
    "keywords": [
        "date",
        "picker",
        "date-picker",
        "react",
        "react-date-picker",
        "react-component"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "bogdanpetru"
        },
        {
            "name": "radubrehar"
        },
        {
            "name": "zippyui"
        }
    ],
    "name": "react-date-picker",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.14.0 || >=15.0.0",
        "react-dom": ">=0.14.0 || >=15.0.0",
        "moment": ">=2.8.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zippyui/react-date-picker.git"
    },
    "scripts": {
        "babel": "babel --out-dir lib src",
        "build": "npm run styles && npm run lib",
        "dev": "webpack-dev-server --progress --config build/webpack.config.js",
        "lib": "rimraf lib && npm run babel",
        "lint": "eslint src/**",
        "prepublish": "npm run build",
        "styles": "theme-builder"
    },
    "version": "5.3.28",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
