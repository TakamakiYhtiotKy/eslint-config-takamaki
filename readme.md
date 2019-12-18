# Why?

The purpose of this repository is to share eslint configs between Takamäki projects. This way we can write uniform code, and it also makes setting up new projects easier.

# Installation

1. Add ""eslint-config-takamaki": "git@bitbucket.org:takamaki/eslint-config-takamaki.git#vx.x.x"" to your package.json ependencies.
2. run "npm install"
3. Install peer dependencies listed in package.json
4. Add "extends": ["takamaki"] to your .eslint config

# Want something changed?

This repository is open to suggestions and discussion. If you want to modify, remove or add a rule make a pull request and add Valtteri Laine as reviewer.

# Overwriting rules

If you want to overwrite a rule you don't like in your project, just define the same rule in your projects own eslint configuration.