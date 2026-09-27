<h1 align="center">Lerna Monorepo</h1>

<p align="center">Minimal monorepo with Lerna and native npm workspaces.</p>

<p align="center">
  <a href="https://github.com/diogopaulino/lerna-js/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/diogopaulino/lerna-js/actions/workflows/ci.yml/badge.svg"></a>
  <img alt="Node.js 22+" src="https://img.shields.io/badge/Node.js-22%2B-339933?logo=node.js&logoColor=white">
  <img alt="Lerna 10" src="https://img.shields.io/badge/Lerna-10-9333EA">
</p>

## Overview

A small reference for package orchestration, testing, versioning and publishing with Lerna while npm handles workspace installation and linking.

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

## Run

```bash
npm ci
npm run check
```

## Commands

| Command | Purpose |
|---|---|
| `npm run check` | Test + validate workspace discovery |
| `npm run list` | List packages |
| `npm run changed` | Show packages changed since the last release |
| `npm run version` | Version changed packages |
| `npm run publish` | Publish already-versioned packages |

## Documentation

- [Lerna](https://lerna.js.org/)
- [npm workspaces](https://docs.npmjs.com/cli/using-npm/workspaces)
