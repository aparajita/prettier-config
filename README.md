# prettier-config

My base Prettier config.

## Installation

```sh
pnpm add -D @aparajita/prettier-config
```

## Usage

After installing, update your project's `prettier.config.js` file to import the rule sets you want:

```js
module.exports = {
  ...require('@aparajita/prettier-config')
  // your overrides here
}
```

---

Read the [Prettier config docs](https://prettier.io) for more information.
