# eslint-config-monolambda
[![npm version](https://img.shields.io/npm/v/eslint-config-monolambda.svg?style=flat)](https://www.npmjs.com/package/eslint-config-monolambda)
[![Travis branch](https://img.shields.io/travis/monolambda/eslint-config-monolambda/master.svg)](https://travis-ci.org/monolambda/eslint-config-monolambda.svg?branch=master)
[![Greenkeeper badge](https://badges.greenkeeper.io/monolambda/eslint-config-monolambda.svg)](https://greenkeeper.io/)
[![Dependency Status](https://gemnasium.com/badges/github.com/monolambda/eslint-config-monolambda.svg)](https://gemnasium.com/github.com/monolambda/eslint-config-monolambda)
[![npm](https://img.shields.io/npm/dt/eslint-config-monolambda.svg)](https://www.npmjs.com/package/eslint-config-monolambda)

## Rules

#### Rule set based on:
- ESLint Recommended
- [JavaScript Standard Style](https://github.com/feross/standard)
- [JavaScript Standard React](https://github.com/feross/eslint-config-standard-react)

#### Opinions:
- Uses `4, spaces` for easier readability
- Keeps most of the rules but overrides nonpragmatic and artifact focused rules.

**Note:** The current ruleset is subject to change and under review, please feel free to send a PR for rules you feel that are over the top.

## Installation:
```sh
npm install eslint-config-monolambda eslint --save
``` 
## Usage
In `.eslintrc`:

```json
{
    "extends": "eslint-config-monolambda"
}
```
