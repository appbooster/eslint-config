# @appbooster/eslint-config

[![Greenkeeper badge](https://badges.greenkeeper.io/appbooster/eslint-config.svg)](https://greenkeeper.io/)

Shared eslint config of Appbooster organization

## Installation

1) Install the package:

```
yarn add --dev @appbooster/eslint-config-base
```

2) Add eslint [config](https://eslint.org/docs/user-guide/configuring#configuration-file-formats) in the root folder and add `extends` option. I.e. using YAML format put file `.eslintrc.yml` with content:

```
extends: '@appbooster/eslint-config-base'
```

## Releasing

To publish new version to npm update version in package.json and create new release. TravisCI will automatically publish new version to npm
