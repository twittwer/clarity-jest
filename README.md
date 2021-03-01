

# ClarityJest

> Reproduction repository for Clarity with Jest as test runner.

This project was generated using [Nx](https://nx.dev).

## Steps to reproduce:

1. `npm install` (+ optionally check the running app with `npm start`)
2. `npm test`

```
 FAIL   clarity-jest  apps/clarity-jest/src/app/app.component.spec.ts
  ● Test suite failed to run

    Jest encountered an unexpected token

    This usually means that you are trying to import a file which Jest cannot parse, e.g. it's not plain JavaScript.

    By default, if Jest sees a Babel config, it will use that to transform your files, ignoring "node_modules".

    Here's what you can do:
     • If you are trying to use ECMAScript Modules, see https://jestjs.io/docs/en/ecmascript-modules for how to enable it.
     • To have some of your "node_modules" files transformed, you can specify a custom "transformIgnorePatterns" in your config.
     • If you need a custom transformation specify a "transform" option in your config.
     • If you simply want to mock your non-JS modules (e.g. binary assets) you can stub them out with the "moduleNameMapper" config option.

    You'll find more details and examples of these config options in the docs:
    https://jestjs.io/docs/en/configuration.html

    Details:

    C:\Users\tw\git\clarity-jest\node_modules\@cds\core\icon\index.js:6
    export * from './icon.element.js';
    ^^^^^^

    SyntaxError: Unexpected token 'export'

      at Runtime.createScriptFromCode (../../node_modules/jest-runtime/build/index.js:1350:14)

Test Suites: 1 failed, 1 total
Tests:       0 total
Snapshots:   0 total
Time:        5.909 s
Ran all test suites.
```
