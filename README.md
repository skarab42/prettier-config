# My shared Prettier config

## Installation

```bash
pnpm add -D prettier @skarab/prettier-config
```

## Configuration

Select one of the three methods below according to your needs and/or preferences.

### Setup in `package.json`

```ts
{
  "prettier": "@skarab/prettier-config"
}
```

### Export from `.prettierrc.json`

```json
"@skarab/prettier-config"
```

### Or extends in `.prettierrc.js`

```js
module.exports = {
  ...require('@skarab/prettier-config'),
  semi: false,
};
```

# My other shared configurations

- [@skarab/eslint](https://github.com/skarab42/eslint-config)
- [@skarab/prettier](https://github.com/skarab42/prettier-config)
- [@skarab/typescript](https://github.com/skarab42/typescript-config)
