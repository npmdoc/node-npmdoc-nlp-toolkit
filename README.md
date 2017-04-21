# npmdoc-nlp-toolkit

#### api documentation for  nlp-toolkit (v0.2.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-nlp-toolkit.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nlp-toolkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nlp-toolkit.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nlp-toolkit)

#### This module covers some basic nlp principles and implementations. Every implementation in this module is written as stream to only hold that data in memory that is currently processed at any step.

[![NPM](https://nodei.co/npm/nlp-toolkit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nlp-toolkit)

- [https://npmdoc.github.io/node-npmdoc-nlp-toolkit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nlp-toolkit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nlp-toolkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nlp-toolkit/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nlp-toolkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nlp-toolkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nlp-toolkit",
    "author": "Alexander Behrens <alexander.behrens.84@gmail.com>",
    "description": "This module covers some basic nlp principles and implementations. Every implementation in this module is written as stream to only hold that data in memory that is currently processed at any step.",
    "url": "https://github.com/Amberlamps/nlp-toolkit",
    "repository": {
        "type": "git",
        "url": "https://github.com/Amberlamps/nlp-toolkit.git"
    },
    "bugs": {
        "url": "https://github.com/Amberlamps/nlp-toolkit/issues"
    },
    "main": "index.js",
    "dependencies": {
        "bayes_fixed": "0.0.6",
        "bluebird": "^3.3.4",
        "debug": "^2.2.0",
        "event-stream": "^3.3.2",
        "lodash": "^4.11.1",
        "mathjs": "^3.1.4",
        "snowball-stemmer.jsx": "^0.2.3",
        "through2": "^2.0.1"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^2.4.5"
    },
    "version": "0.2.6",
    "keywords": [
        "nlp",
        "porter",
        "stemmer",
        "tokenize",
        "tokenizer",
        "stopwords",
        "tfidf",
        "idf",
        "frequency",
        "stream",
        "frequency distribution",
        "cross validation",
        "term frequency"
    ],
    "publishConfig": {
        "registry": "https://registry.npmjs.org"
    },
    "licence": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
