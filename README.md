# eslint-plugin-import-typescript-resolver

[![Greenkeeper badge](https://badges.greenkeeper.io/alexgorbatchev/eslint-plugin-import-typescript-resolver.svg)](https://greenkeeper.io/)

This plugin allows you to use `eslint-plugin-import` with `.ts` and `.tsx` files.

![](screenshot.png)

## Installation

```
npm install --save-dev eslint-plugin-import-typescript-resolver
```

Add the following to your eslint config:

```
"settings": {
  "import/resolver": {
    "node": true,
    "eslint-plugin-import-typescript-resolver": true
  }
}
```
