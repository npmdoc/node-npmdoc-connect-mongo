# api documentation for  [connect-mongo (v1.3.2)](https://github.com/kcbanner/connect-mongo#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-connect-mongo.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-connect-mongo) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-connect-mongo.svg)](https://travis-ci.org/npmdoc/node-npmdoc-connect-mongo)
#### MongoDB session store for Express and Connect

[![NPM](https://nodei.co/npm/connect-mongo.png?downloads=true)](https://www.npmjs.com/package/connect-mongo)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect-mongo/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-connect-mongo_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect-mongo/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-connect-mongo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-connect-mongo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/kcbanner/connect-mongo/issues"
    },
    "contributors": [
        {
            "name": "Casey Banner",
            "email": "kcbanner@gmail.com"
        },
        {
            "name": "Jerome Desboeufs",
            "email": "jerome.desboeufs@gmail.com"
        }
    ],
    "dependencies": {
        "bluebird": "^3.0",
        "mongodb": ">= 1.2.0 <3.0.0"
    },
    "description": "MongoDB session store for Express and Connect",
    "devDependencies": {
        "babel-cli": "^6.3.17",
        "babel-plugin-transform-es2015-arrow-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoping": "^6.3.13",
        "babel-plugin-transform-es2015-classes": "^6.3.15",
        "babel-plugin-transform-es2015-object-super": "^6.3.13",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-register": "^6.3.13",
        "eslint": "^3.1.1",
        "expect.js": "^0.3.1",
        "express-session": ">= 1.0.0",
        "istanbul": "^0.4.1",
        "mocha": "^2.3.4",
        "mongoose": ">= 2.6.0 < 5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7cbf58dfff26760e5e00e017d0a85b4bc90b9d37",
        "tarball": "https://registry.npmjs.org/connect-mongo/-/connect-mongo-1.3.2.tgz"
    },
    "gitHead": "f4c8fa5d04777c0017f5123a10b71577de248d45",
    "homepage": "https://github.com/kcbanner/connect-mongo#readme",
    "keywords": [
        "connect",
        "mongo",
        "mongodb",
        "session",
        "express"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kcbanner",
            "email": "kcbanner@gmail.com"
        },
        {
            "name": "jdesboeufs",
            "email": "jerome.desboeufs@gmail.com"
        }
    ],
    "name": "connect-mongo",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kcbanner/connect-mongo.git"
    },
    "scripts": {
        "cover": "istanbul cover -x 'src-es5/**' _mocha",
        "lint": "eslint src test",
        "prepublish": "npm run transpile",
        "test": "npm run lint && npm run transpile && npm run cover",
        "test-es5": "npm run transpile && npm run test-unit-es5",
        "test-unit": "mocha",
        "test-unit-es5": "mocha --compilers js:babel-register",
        "transpile": "babel src --out-dir src-es5"
    },
    "version": "1.3.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module connect-mongo](#apidoc.module.connect-mongo)



# <a name="apidoc.module.connect-mongo"></a>[module connect-mongo](#apidoc.module.connect-mongo)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
