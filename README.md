<h1 align="center">Lerna Monorepo</h1>

<p align="center">
  Small modern monorepo using <strong>Lerna 10</strong> and native <strong>npm workspaces</strong>.
</p>

<p align="center">
  <a href="https://github.com/diogopaulino/lerna-js/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/diogopaulino/lerna-js/actions/workflows/ci.yml/badge.svg"></a>
  <img alt="Node.js 22+" src="https://img.shields.io/badge/Node.js-22%2B-339933?logo=node.js&logoColor=white">
  <img alt="Lerna 10" src="https://img.shields.io/badge/Lerna-10-9333EA">
</p>

## About

A minimal reference for package orchestration, versioning and publishing in a current Lerna workspace.

The original repository used Lerna 3. It now follows the modern model where **npm manages workspaces** and **Lerna handles monorepo workflows**.

## Structure

```text
packages/
└── hello/
    ├── src/
    ├── test/
    └── package.json

lerna.json
package.json
```

## Quick start

```bash
npm install
npm test
```

## Commands

| Command | Purpose |
|---|---|
| `npm test` | Run workspace tests |
| `npm run list` | List packages |
| `npm run changed` | Show packages changed since the last release |
| `npm run version` | Version changed packages |
| `npm run publish` | Publish already-versioned packages |

## Stack

- Lerna 10.0.1
- npm workspaces
- Node.js 22+
- Native Node.js test runner

## Learn more

- [Lerna documentation](https://lerna.js.org/)
- [npm workspaces](https://docs.npmjs.com/cli/using-npm/workspaces)
