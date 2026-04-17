# codemie-playwright-typescript

Automated web testing project built with [Playwright](https://playwright.dev/) and TypeScript.

## Requirements

- Node.js >= 18
- npm >= 9

## Setup

```bash
npm install
npx playwright install
```

## Scripts

| Command                | Description               |
| ---------------------- | ------------------------- |
| `npm test`             | Run all tests (headless)  |
| `npm run test:ui`      | Open Playwright UI mode   |
| `npm run test:headed`  | Run tests in headed mode  |
| `npm run test:debug`   | Run tests in debug mode   |
| `npm run report`       | Open HTML test report     |
| `npm run lint`         | Check code with ESLint    |
| `npm run lint:fix`     | Auto-fix ESLint issues    |
| `npm run format`       | Format code with Prettier |
| `npm run format:check` | Check formatting          |

## Project structure

```
tests/          # Test files (*.spec.ts)
playwright.config.ts
tsconfig.json
eslint.config.mjs
.prettierrc.json
```
