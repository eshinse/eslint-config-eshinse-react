# eslint-config-eshinse-react

Configuration:

* Enables JSX
* React and JSX related rules.

Peer dependencies:

* [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react)
* [eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y)

## Install

`npm install --save-dev eslint-config-eshinse-react`

## Use

The order of the extensions matter; each additional configuration extends the preceding configurations.

**.eslintrc.yaml:**

```
---

extends:
  - eshinse
  - eshinse-jsdoc
  - eshinse-react
  - eshinse-react-native
```

**.eslintrc.json:**

```json
{
  "extends": [
    "eshinse",
    "eshinse-jsdoc",
    "eshinse-react",
    "eshinse-react-native"
  ]
}
```

## Licence (Apache-2.0)

See [LICENCE](LICENCE).

## Additional ESLint configs

* [eslint-config-eshinse](https://github.com/eshinse/eslint-config-eshinse)
* [eslint-config-eshinse-jsdoc](https://github.com/eshinse/eslint-config-eshinse-jsdoc)
* [eslint-config-eshinse-react-native](https://github.com/eshinse/eslint-config-eshinse-react-native)
