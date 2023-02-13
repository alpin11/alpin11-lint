
![alpin11-indigo](https://user-images.githubusercontent.com/37235804/218451376-4725aaae-b6b9-469a-85fc-c9265100dd49.svg)

# Alpin11 Lint

An extendable ESLint config used for all projects at Alpin11.

## Installation

First make sure you remove any previous eslint configs as well as eslint itself.

Install our lint config with npm or yarn:

```bash
  yarn add @alpin11/lint
```
or
```bash
npm i @alpin11/lint
```
After installation, create a `.eslintrc` in your project root and add the following contents
```json
{
  "extends": [
    "./node_modules/@alpin11/lint/.eslintrc",
  ]
}
```
## Config extension

The config can easily be extended or overridden by adding your rules to the `rules` section of your `.eslintrc`.
## Acknowledgements
Heavily based on [JohnDeved's ESLint Config](https://github.com/JohnDeved/undefined-lint) which is in turn based on [Standard JS](https://standardjs.com/) and [Standard with Typescript](https://github.com/standard/eslint-config-standard-with-typescript)

## Authors

- [@JohnDeved](https://www.github.com/JohnDeved)
- [@dominikager](https://www.github.com/dominikager)
- [@DeltaSAMP](https://www.github.com/DeltaSAMP)
- [@halykon](https://www.github.com/halykon)
