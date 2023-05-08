
![alpin11-indigo](https://user-images.githubusercontent.com/37235804/218451376-4725aaae-b6b9-469a-85fc-c9265100dd49.svg)

# ALPIN11 Lint

An extendable ESLint config used for all projects at Alpin11.

## Installation

First make sure you remove any previous eslint configs as well as eslint itself.

Install our lint config with npm or yarn:

```bash
  yarn add -D @alpin11/eslint-config
```
or
```bash
npm i --save-dev @alpin11/eslint-config
```
After installation, create a `.eslintrc` in your project root and add the following contents
```json
{
  "extends": [
    "@alpin11",
  ]
}
```
## Config extension

The config can easily be extended or overridden by adding your rules to the `rules` section of your `.eslintrc`.

## Changelog 

### v0.3.0 and later 

- Uses pnpm as package manager
- Uses `eslint-config-standard-with-typescript@^34.0.0` 


## Acknowledgements
Heavily based on [JohnDeved's ESLint Config](https://github.com/JohnDeved/undefined-lint) which is in turn based on [Standard JS](https://standardjs.com/) and [Standard with Typescript](https://github.com/standard/eslint-config-standard-with-typescript)

## Authors

- [@JohnDeved](https://www.github.com/JohnDeved)
- [@dominikager](https://www.github.com/dominikager)
- [@DeltaSAMP](https://www.github.com/DeltaSAMP)
- [@halykon](https://www.github.com/halykon)
- [@davidhoeck](https://www.github.com/davidhoeck)
