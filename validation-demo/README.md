# AutoDevOps Validation Demo Fixture

This directory is a minimal, dependency-free Node.js test fixture for the local AutoDevOps runner.

It is intentionally self-contained:
- `index.js` exports a single `add(a, b)` function.
- `test/add.test.js` uses Node.js's built-in `node:test` runner.
- No package installation is required.

The fixture is intended for safe patch-validation experiments. Do not put credentials or secrets here.
