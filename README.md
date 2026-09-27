# Lerna + npm workspaces

A small, current monorepo example using **Lerna 10** with native **npm workspaces**.

## Stack

- Lerna 10.0.1
- npm workspaces
- Native Node.js test runner
- Node.js 22+

## Setup

```bash
npm install
npm test
```

## Useful commands

```bash
npm run list
npm run changed
npm run version
```

Lerna now focuses on monorepo orchestration and publishing while the package manager handles dependency installation and workspace linking. This repository follows that model instead of the old Lerna 3 bootstrap workflow.

Docs: https://lerna.js.org/
