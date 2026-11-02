# SeaStore

SeaStore is a seafood ecommerce project. This repository starts with a pnpm workspace and Turborepo; application and shared-package choices will be added in the next setup phase.

## Prerequisites

- Node.js 22
- pnpm 10.34.9 (pinned in `package.json`)

## Workspace commands

```powershell
pnpm install
pnpm dev
pnpm build
pnpm lint
pnpm typecheck
```

Add applications under `apps/` and shared packages under `packages/`. Each workspace needs its own `package.json` and scripts for the root commands it supports.


