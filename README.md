# Statsfm Style Guide

The ESLint config Statsfm uses.

## Installation

There are four packages available. Each of them can be installed with `yarn add --dev @statsfm/eslint-config-<name>`.
The following packages can be installed:

```txt
@statsfm/eslint-config-base
@statsfm/eslint-config-jest
@statsfm/eslint-config-typescript
@statsfm/eslint-config-vue
```

You may then extend the installed package(s) in your `.eslintrc.js`, like this:

```js
module.exports = {
  extends: [
    "@statsfm/base",
    "@statsfm/jest",
    "@statsfm/typescript",
    "@statsfm/vue",
  ],
};
```

Feel free to remove any configs you don't need.

## License

This project is licensed under the 3-Clause BSD license.
