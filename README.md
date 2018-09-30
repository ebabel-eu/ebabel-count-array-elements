# ebabel-count-array-elements
[![Build Status](https://travis-ci.org/ebabel-eu/ebabel-count-array-elements.svg?branch=master)](https://travis-ci.org/ebabel-eu/ebabel-count-array-elements)

Returns an object that counts how many times each element is present in a given array.

## Module install and usage in your game

### Install
```
npm install --save ebabel-count-array-elements
```

### Usage
```
const count-array-elements = require('ebabel-count-array-elements');

const result = count-array-elements(['orc', 'goblin', 'orc', 'orc', 'elf']);
```

## Development of this module
Fork this repository on Github, `git clone` your repository, checkout the develop branch, and when you are done, submit a pull request from your repository develop branch to this repository develop branch.

* fork this repository on github.com
* git clone your forked repository.
* git checkout develop

### First step when developing
```
npm install
```

### Run linting and unit tests
```
npm test
```

An html coverage report is to be found in the `coverage` folder.

### Generate documentation
```
npm run jsdoc
```

The generated documentation is to be found in the `docs` folder.
