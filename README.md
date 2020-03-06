# eslint-config-ego

[![npm](https://img.shields.io/npm/v/eslint-config-ego.svg)](https://www.npmjs.com/package/eslint-config-ego)

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html) for the e.GO style guide

## Installation

```
$ npm install --save-dev eslint eslint-config-ego
```

## Usage

Once the `eslint-config-ego` package is installed, you can use it by specifying `ego` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

Create a `.eslintrc.js` file in the root folder of your project and use the following skeleton:

```js
module.exports = {
    "extends": "ego",
    "rules": {
      // Additional, per-project rules...
    }
}
```

### Visual Studio Code

First install [ESLint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) for [Visual Studio Code](https://code.visualstudio.com/) by [Dirk Baeumer](https://marketplace.visualstudio.com/publishers/dbaeumer).

Then setup your `settings.json` inside your `.vscode` subfolder by adding the following entries:

```json
{
    "editor.formatOnSave": true,
    "editor.tabSize": 4,
    "eslint.quiet": false,
    "eslint.enable": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    }
}
```

## License

MIT © [e.GO Digital GmbH](https://e-go-digital.com/), Aachen, Germany
