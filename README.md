# @modyqyw/stylelint-config-css

A Stylelint shareable config for css. Also support miniprograms.

## Usage

- Install the config.

```sh
npm i stylelint@~13.3.0 @modyqyw/stylelint-config-css@~1.0.0 -D
```

For yarn, run scripts below.

```sh
yarn add stylelint@~13.3.0 @modyqyw/stylelint-config-css@~1.0.0 -D
```

- Set up.

```js
// stylelint.config.js
module.exports = {
  extends: ["@modyqyw/stylelint-config-css"],
};
```

## VSCode

- Install plugins.
  - [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
- Set up `Settings.json`. Then `F1 => File: Save`.

```json
{
  "css.validate": false,
  "css.validate": false,
  "css.validate": false,
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  }
}
```

## More Config

- [@modyqyw/stylelint-config-less](https://github.com/Millcloud/stylelint-config-less)
- [@modyqyw/stylelint-config-scss](https://github.com/Millcloud/stylelint-config-scss)

## License

[MIT](./LICENSE)

Copyright (c) 2020-present Millcloud