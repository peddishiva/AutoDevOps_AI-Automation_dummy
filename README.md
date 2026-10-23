# AutoDevOps Validation Demo

This branch contains a minimal, dependency-free Node.js project for testing the local AutoDevOps patch-validation runner.

## Files

- `index.js` exports `add(a, b)`.
- `test/add.test.js` uses Node.js built-in `node:test`.
- `package.json` defines `npm test` as `node --test`.

## Test

Run on Node.js 22 or later:

```sh
node --test
```

No package installation is required. This branch is a test fixture for local validation only.
