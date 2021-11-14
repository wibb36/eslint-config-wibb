# Sam Wibb's eslint config 💪

This package provides basic eslint and prettier configuration as an extensible shared config for react/react-native projects.

```sh
yarn add --dev eslint-config-wibb typescript
```

## Usage

Create the following files at the root of your project/monorepo:

**`.eslintrc`**

```json
{
  "extends": ["eslint-config-wibb"]
}
```

**`.prettierrc.js`**

```js
module.exports = require('eslint-config-wibb/prettier')
```

## Improving this config
- Adding typescript configuration