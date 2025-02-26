# @igniter/eslint-config

[![npm version](https://badge.fury.io/js/@igniter%2Feslint-config.svg)](https://www.npmjs.com/package/@igniter/eslint-config)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A carefully crafted ESLint and Prettier configuration preset for modern JavaScript and TypeScript projects. Enforce consistent code style and catch potential errors before they make it to production.

## Features

- 🎯 Optimized for TypeScript and JavaScript
- ⚡ Works seamlessly with Prettier
- 🔧 Zero configuration needed
- 📦 Easy to extend and customize

## Installation

```bash
# Using npm
npm install --save-dev @igniter/eslint-config

# Using yarn
yarn add -D @igniter/eslint-config

# Using pnpm
pnpm add -D @igniter/eslint-config
```

## Usage

Add the following to your `.eslintrc.json` (or `.eslintrc.js`):

```json
{
  "extends": "@igniter/eslint-config"
}
```

### With Prettier

This config includes Prettier settings. Add a `prettier.config.js` to your project:

```javascript
module.exports = require('@igniter/eslint-config/prettier')
```

## What's Included

This configuration includes settings for:

- ESLint recommended rules
- TypeScript ESLint rules
- React and JSX/TSX support
- Import/Export rules
- Prettier integration

## Customization

You can override any rules by adding them to your ESLint config file:

```json
{
  "extends": "@igniter/eslint-config",
  "rules": {
    // Your custom rules here
  }
}
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

MIT License - see the [LICENSE](LICENSE) file for details

## Support

- 📝 [Documentation](https://github.com/felipebarcelospro/igniter-eslint-config)
- 🐛 [Issue Tracker](https://github.com/felipebarcelospro/igniter-eslint-config/issues)
- 💬 [Discussions](https://github.com/felipebarcelospro/igniter-eslint-config/discussions)

---

Made with ❤️ by Felipe Barcelos
