#hola
##DEMO NODE TDD PARA ALGORITMOS JS


<h1 align=center>
  <a href="http://chaijs.com" title="Chai Documentation">
  </a>
  <br>
  chai
</h1>
<p align=center>
1-crear el proyecto github
echo "# nodetdd" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/nataliaMarzec/nodetdd.git
git push -u origin master
<br/>
2-hacer:
npm init    'dentro del proyecto'
npm install 
npm install chai

<p align=center>
  Chai is a BDD / TDD assertion library for <a href="http://nodejs.org">node</a> and the browser that can be delightfully paired with any javascript testing framework.
</p>

<p align=center>
  <a href="./LICENSE">
    <img
      alt="license:mit"
      src="https://img.shields.io/badge/license-mit-green.svg?style=flat-square"
    />
  </a>
  <a href="https://github.com/chaijs/chai/releases">
    <img
      alt="tag:?"
      src="https://img.shields.io/github/tag/chaijs/chai.svg?style=flat-square"
    />
  </a>
  <a href="https://www.npmjs.com/package/chai">
    <img
      alt="node:?"
      src="https://img.shields.io/badge/node-%3E=4.0-blue.svg?style=flat-square"
    />
  </a>
  <br/>
  <a href="https://saucelabs.com/u/chaijs">
    <img
      alt="Selenium Test Status"
      src="https://saucelabs.com/browser-matrix/chaijs.svg"
    />
  </a>
  <br/>
  <a href="https://www.npmjs.com/packages/chai">
    <img
      alt="downloads:?"
      src="https://img.shields.io/npm/dm/chai.svg?style=flat-square"
    />
  </a>
  <a href="https://travis-ci.org/chaijs/chai">
    <img
      alt="build:?"
      src="https://img.shields.io/travis/chaijs/chai/master.svg?style=flat-square"
    />
  </a>
  <a href="https://codecov.io/gh/chaijs/chai">
    <img
      alt="coverage:?"
      src="https://img.shields.io/codecov/c/github/chaijs/chai.svg?style=flat-square"
    />
  </a>
  <a href="">
    <img
      alt="devDependencies:?"
      src="https://img.shields.io/david/chaijs/chai.svg?style=flat-square"
    />
  </a>
  <br/>
  <a href="https://chai-slack.herokuapp.com/">
    <img
      alt="Join the Slack chat"
      src="https://img.shields.io/badge/slack-join%20chat-E2206F.svg?style=flat-square"
    />
  </a>
  <a href="https://gitter.im/chaijs/chai">
    <img
      alt="Join the Gitter chat"
      src="https://img.shields.io/badge/gitter-join%20chat-D0104D.svg?style=flat-square"
    />
  </a>
  <a href="https://opencollective.com/chaijs">
    <img
      alt="OpenCollective Backers"
      src="https://opencollective.com/chaijs/backers/badge.svg?style=flat-square"
    />
  </a>
</p>

## Installation

### Node.js

`chai` is available on [npm](http://npmjs.org). To install it, type:

    $ npm install chai

### Browsers

You can also use it within the browser; install via npm and use the `chai.js` file found within the download. For example:

```html
<script src="./node_modules/chai/chai.js"></script>
```

## Usage

Import the library in your code, and then pick one of the styles you'd like to use - either `assert`, `expect` or `should`:

```js
var chai = require('chai');  
var assert = chai.assert;    // Using Assert style
var expect = chai.expect;    // Using Expect style
var should = chai.should();  // Using Should style
```

### Pre-Native Modules Usage (_registers the chai testing style globally_)

```js
require('chai/register-assert');  // Using Assert style
require('chai/register-expect');  // Using Expect style
require('chai/register-should');  // Using Should style
```

### Pre-Native Modules Usage (_as local variables_)

```js
const { assert } = require('chai');  // Using Assert style
const { expect } = require('chai');  // Using Expect style
const { should } = require('chai');  // Using Should style
should();  // Modifies `Object.prototype`

const { expect, use } = require('chai');  // Creates local variables `expect` and `use`; useful for plugin use
```

### Native Modules Usage (_registers the chai testing style globally_)

```js
import 'chai/register-assert';  // Using Assert style
import 'chai/register-expect';  // Using Expect style
import 'chai/register-should';  // Using Should style
```

### Native Modules Usage (_local import only_)

```js
import { assert } from 'chai';  // Using Assert style
import { expect } from 'chai';  // Using Expect style
import { should } from 'chai';  // Using Should style
should();  // Modifies `Object.prototype`
```

### Usage with Mocha

```bash
mocha spec.js -r chai/register-assert  # Using Assert style
mocha spec.js -r chai/register-expect  # Using Expect style
mocha spec.js -r chai/register-should  # Using Should style
```

### Related Projects

- [chaijs / chai-docs](https://github.com/chaijs/chai-docs): The chaijs.com website source code.
- [chaijs / assertion-error](https://github.com/chaijs/assertion-error): Custom `Error` constructor thrown upon an assertion failing.
- [chaijs / deep-eql](https://github.com/chaijs/deep-eql): Improved deep equality testing for Node.js and the browser.
- [chaijs / type-detect](https://github.com/chaijs/type-detect): Improved typeof detection for Node.js and the browser.
- [chaijs / check-error](https://github.com/chaijs/check-error): Error comparison and information related utility for Node.js and the browser.
- [chaijs / loupe](https://github.com/chaijs/loupe): Inspect utility for Node.js and browsers.
- [chaijs / pathval](https://github.com/chaijs/pathval): Object value retrieval given a string path.
- [chaijs / get-func-name](https://github.com/chaijs/get-func-name): Utility for getting a function's name for node and the browser.




