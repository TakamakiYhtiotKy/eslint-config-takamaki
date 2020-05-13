# Why?

The purpose of this repository is to share eslint configs between Takamäki projects. This way we can write uniform code, and it also makes setting up rules for new projects faster.

# Installation

1. ```npm i @takamaki-group/eslint-config-takamaki --save-dev```
2. Install peer dependencies listed in package.json
3. Add ```"extends": ["@takamaki-group/eslint-config-takamaki"]``` to your .eslint config

# Overwriting rules

If you want to overwrite a rule you don't like in your project, just define the same rule in your projects own eslint configuration.

# Typescript

You should use ESlint with TypeScript as TSLint was deprecated in 2019. 

To use this config with Typescript add the following to your eslint config:

```
'extends': [
    'plugin:@typescript-eslint/eslint-recommended',
    "plugin:@typescript-eslint/recommended"
],
```

Then install this package: https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin