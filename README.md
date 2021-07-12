# typescript-node-template

A boilerplate/template for TypeScript projects in Node with sensible linting and formatting defaults.

- Forces [**strict mode**](https://www.typescriptlang.org/tsconfig/#strict) for TypeScript.
- Configured for [**CommonJS**](https://nodejs.org/api/modules.html) modules instead of [ESM](https://nodejs.org/api/esm.html) since it is better supported.
- Uses [**Yarn 2**](https://yarnpkg.com) as the package manager with the following settings/plugins:
  - Configured to use `node_modules` instead of [PnP](https://yarnpkg.com/features/pnp) for greater compatability.
  - [typescript](https://yarnpkg.com/api/modules/plugin_typescript.html)
  - [upgrade-interactive](https://yarnpkg.com/api/modules/plugin_interactive_tools.html)
- [**TypeScript ESLint**](https://github.com/typescript-eslint/typescript-eslint) with the following plugins/configs:
  - [Unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)
  - [SonarJS](https://github.com/SonarSource/eslint-plugin-sonarjs)
  - [eslint-comments](https://github.com/mysticatea/eslint-plugin-eslint-comments)
  - [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)
  - [eslint-formatter-pretty](https://github.com/sindresorhus/eslint-formatter-pretty)
- [**Prettier**](https://prettier.io) with the following plugins/options:
  - [sort-imports](https://github.com/trivago/prettier-plugin-sort-imports)
  - [sh](https://github.com/rx-ts/prettier/tree/master/packages/sh)
  - [pkg](https://github.com/rx-ts/prettier/tree/master/packages/pkg)
  - Options:
    `printWidth: 120`
    `semi: false`
    `singleQuote: true`
    `trailingComma: all`
- **VSCode settings**:
  - `"editor.defaultFormatter": "esbenp.prettier-vscode"` - Sets Prettier as the default formatter.
  - `"editor.formatOnSave": true` - Format with Prettier on save.
  - You must have the [VSCode Prettier plugin](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) installed.
  - It's also recommended that you install the [VSCode ESLint plugin](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint).

Any suggestions/improvements are more than welcome. Please submit an Issue or PR.
