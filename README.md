
[![Toreda](https://content.toreda.com/logo/toreda-logo.png)](https://www.toreda.com)

# `@toreda/prettier-config`

`prettier-config` for Toreda TypeScript projects.

&nbsp;
# Usage

Requires Prettier 3.0 or later. Prettier is a peer dependency, so install it alongside this package.

&nbsp;
# Add to Project
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

&nbsp;

# Examples

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

&nbsp;

# Legal

## License

[MIT](LICENSE) &copy; Toreda, Inc.

## Copyright
Copyright &copy; 2019 - 2026 Toreda, Inc. All Rights Reserved.

https://www.toreda.com
