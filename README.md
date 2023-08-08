# Test Volar Fast

## Setp 1
use vscode open project
```bash
pnpm i # If you don't have pnpm installed, run: npm install -g pnpm
```
## Setp 2
 `volar 1.8.8、ts vue plugin 1.8.8`,open `managed mode`, open file:
- `App.vue `
- `/api/index.ts`

## Step 3

- delete `import { testApi } from './api'` in  `App.vue `
- delete `import type { TestType } from '~/type'` in `/api/index.ts`

## Step 4

hover `TestType`、`testApi`, Fast Fix feature (auto import) is lost

## Step 5
`off managed mode`, reload vscode window, only .ts file have Fast Fix

## Step 6
- `open managed mode`, switch `volar 1.2.0` version, reload vscode window,
- .vue、.ts have Fast Fix (auto import)


**  vscode version is last
