# ESLint Config PostCSS

> An ESLint shareable config for PostCSS and plugins.

If you have any question about a rule or want to discuss about it, please open an issue.

## Usage

### Modern ES

```sh
$ npm install --save-dev eslint-config-postcss eslint-config-logux eslint-config-standard eslint-plugin-promise eslint-plugin-jest eslint-plugin-node eslint-plugin-standard eslint-plugin-security eslint-plugin-import eslint-plugin-prefer-let
```

Add to your eslint configuration (here, in `package.json`)

```json
{
  "eslintConfig": {
    "extends": "eslint-config-postcss"
  }
}
```

### Old ES5

```sh
$ npm install --save-dev eslint-config-postcss eslint-config-logux eslint-config-standard eslint-plugin-promise eslint-plugin-jest eslint-plugin-node eslint-plugin-es5 eslint-plugin-standard eslint-plugin-security eslint-plugin-import
```

To use only ES5 rule set:

```json
{
  "eslintConfig": {
    "extends": "eslint-config-postcss/es5"
  }
}
```

---

## [LICENSE](LICENSE)
