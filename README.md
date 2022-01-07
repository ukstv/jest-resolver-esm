# Jest Resolver ESM

Allows Jest to handle [conditional exports](https://nodejs.org/api/packages.html#packages_conditional_exports).
Uses `import` and `node` exports.

Under the hood:
- use [enhanced-resolve](https://www.npmjs.com/package/enhanced-resolve) from Webpack by default,
- if enhanced-resolve fails, use vanilla Jest resolver.
