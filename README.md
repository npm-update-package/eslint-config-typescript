[![npm version](https://badge.fury.io/js/@npm-update-package%2Feslint-config-typescript.svg)](https://badge.fury.io/js/@npm-update-package%2Feslint-config-typescript)
[![lint](https://github.com/npm-update-package/eslint-config-typescript/actions/workflows/lint.yml/badge.svg)](https://github.com/npm-update-package/eslint-config-typescript/actions/workflows/lint.yml)
[![ESLint Recommended](https://img.shields.io/badge/eslint-recommended-%234B32C3)](https://github.com/eslint-recommended)

# @npm-update-package/eslint-config-typescript

ESLint Shareable Config for TypeScript

## Peer dependencies

- [@eslint-recommended/eslint-config-typescript](https://www.npmjs.com/package/@eslint-recommended/eslint-config-typescript)
- [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin)
- [eslint](https://www.npmjs.com/package/eslint)
- [eslint-config-standard-with-typescript](https://www.npmjs.com/package/eslint-config-standard-with-typescript)
- [eslint-plugin-eslint-comments](https://www.npmjs.com/package/eslint-plugin-eslint-comments)
- [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)
- [eslint-plugin-import-newlines](https://www.npmjs.com/package/eslint-plugin-impor-newlines)
- [eslint-plugin-jsdoc](https://www.npmjs.com/package/eslint-plugin-jsdoc)
- [eslint-plugin-n](https://www.npmjs.com/package/eslint-plugin-n)
- [eslint-plugin-promise](https://www.npmjs.com/package/eslint-plugin-promise)
- [eslint-plugin-tsdoc](https://www.npmjs.com/package/eslint-plugin-tsdoc)
- [eslint-plugin-unicorn](https://www.npmjs.com/package/eslint-plugin-unicorn)
- [typescript](https://www.npmjs.com/package/typescript)

## Installation

### npm@>=7

Install `@npm-update-package/eslint-config-typescript`.

```sh
npm i -D @npm-update-package/eslint-config-typescript
```

### npm@<7

Install `@npm-update-package/eslint-config-typescript` and its peer dependencies.

```sh
npm i -D \
  @eslint-recommended/eslint-config-typescript \
  @typescript-eslint/eslint-plugin \
  eslint \
  eslint-config-standard-with-typescript \
  eslint-plugin-eslint-comments \
  eslint-plugin-import \
  eslint-plugin-import-newlines \
  eslint-plugin-jsdoc \
  eslint-plugin-n \
  eslint-plugin-promise \
  eslint-plugin-tsdoc \
  eslint-plugin-unicorn \
  typescript \
  @npm-update-package/eslint-config-typescript
```

## Usage

Add `@npm-update-package/eslint-config-typescript` to `extends` of your ESLint config.

```json
{
  "extends": [
    "@npm-update-package/eslint-config-typescript"
  ]
}
```
