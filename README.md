# eslint-config-superology-vue-typescript

Shared ESLint config for Vue based projects at Superology using TypeScript.

![@superology/eslint-config-vue](https://svgshare.com/i/dvq.svg "ESLint Vue config by Superology (TypeScript)")

ESLint statically analyzes your code to quickly find problems. ESLint is built into most text editors and you can run ESLint as part of your continuous integration pipeline.

- [Getting Started](https://eslint.org/docs/user-guide/getting-started)
- [Configuring](https://eslint.org/docs/user-guide/configuring)
- [Rules](https://eslint.org/docs/rules/)
- [Shareable Configs](https://eslint.org/docs/developer-guide/shareable-configs)

## Usage

### Install the configuration

```bash
npm install eslint-config-superology-vue-typescript --save-dev
```

Also make sure you have peer dependencies installed:

```bash
npm install eslint prettier jest eslint-plugin-import eslint-config-superology-vue @rushstack/eslint-patch --save-dev
```

#### IMPORTANT

This plugin really requires `eslint-config-superology-vue` to work correctly and to apply full Superology linting rules.

### Add to ESLint configuration

```json
{
  "extends": "eslint-config-superology-vue-typescript"
}
```

_Using `.eslintrc` file_

or

```js
module.exports = {
  extends: "eslint-config-superology-vue-typescript",
};
```

_if using `.eslintrc.js` file_

## Suggestions?

Create a discussion on [GitHub](/discussions) or [learn how to make a contribution](https://github.com/firstcontributions/first-contributions).
