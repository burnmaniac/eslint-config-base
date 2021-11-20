# @burnmaniac/eslint-config-base

This package contains ESLint configuration for JavaScript projects.

## Usage

Install:

```sh
$ npm install --save-dev @burnmaniac/eslint-config-base
```

or with `yarn`

```sh
$ yarn add --dev @burnmaniac/eslint-config-base
```

Create a file named `.eslintrc` in the root folder of your project:

```json
{
    "root": true,
    "extends": "@burnmaniac/eslint-config-base",
    "rules": {
        "valid-jsdoc": "warn",
        "require-jsdoc": "off"
    }
}
```

Learn more about [configuring ESLint](http://eslint.org/docs/user-guide/configuring) on the ESLint website.
