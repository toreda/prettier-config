
# `@toreda/prettier-config`

![Toreda](https://content.toreda.com/logo/toreda-logo.png)

Toreda's official organization-wide `prettier-config` for TypeScript projects.

## Usage

### Install using yarn

```bash
$ yarn add @toreda/prettier-config --dev
```

### Install using npm
```bash
$ npm add @toreda/prettier-config --save-dev
```


### Add to Project
1. Navigate to your project's root folder.
2. Open `package.json`
3. Add a `prettier` key pointing to `@toreda/prettier-config`:

```jsonc
{
  // ...
  "prettier": "@toreda/prettier-config"
}
```

**Note: If your `package.json` already contains a `prettier` key, you will need to replace the value with the value shown above.**

#### Example

Here's a complete `package.json` example using the prettier key:

```json
{
  "name": "sample-project-here",
  "version": "1.5.3",
  "description": "Sample project",
  "main": "./dist/index",
  "scripts": {
    "test": "yarn jest --coverage"
  },
  "author": "Toreda, Inc.",
  "license": "MIT",
  "prettier": "@toreda/prettier-config"
}

```