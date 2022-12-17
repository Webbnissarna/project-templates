# Node-TypeScript

Template for a NodeJS project, enforcing TypeScript. This is for vanilla NodeJS projects such as a basic server or cli.

## Commands

| Command      | Description                                                   |
| ------------ | ------------------------------------------------------------- |
| `yarn start` | Run normally. Defaults to running `src/index.ts`.             |
| `yarn dev`   | Run `src/index.ts` and watch and reload for any file changes. |
| `yarn test`  | Run tests.                                                    |

## Stack

- `yarn` as package manager
- `jest` as test runner
- `ts-node` as script runner
- `nodemon` as script runner for dev
- `eslint` as linter, with opinionated plugins and settings
- `prettier` as formatter
- `commitizen` as commit handler, with `cz-conventional-emoji` as format
