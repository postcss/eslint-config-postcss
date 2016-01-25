# eslint-config-postcss [![Travis](https://travis-ci.org/postcss/eslint-config-postcss.svg)](https://travis-ci.org/postcss/eslint-config-postcss)

> An ESLint shareable config for postcss and plugins.

If you have any question about a rule or want to discuss about it, please open an issue.

## Install

```console
$ npm i -D eslint eslint-config-postcss
```

## Usage

### Modern ES

Add to your eslint configuration (here, in `package.json`)

```json
{
  "eslintConfig": {
    "extends": "eslint-config-postcss"
  }
}
```

### Old ES5

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
