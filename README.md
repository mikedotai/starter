# TypeScript Starter 2025

Modern TypeScript starter template with best practices for 2025.

## Features

- ⚡ **ES2024 Support** - Latest ECMAScript features
- 🎯 **Strict TypeScript** - Strict mode enabled for type safety
- 🧹 **ESLint 9** - Modern linting with typescript-eslint
- 💅 **Prettier** - Code formatting
- 🚀 **Fast Execution** - Using tsx for development
- 📦 **ESM Ready** - ES modules support

## Quick Start

### Installation

```bash
pnpm install
```

### Development

Run TypeScript directly without compilation:

```bash
pnpm run dev
```

### Build

Compile TypeScript to JavaScript:

```bash
pnpm run build
```

### Production

Run compiled JavaScript:

```bash
pnpm start
```

## Scripts

| Script                | Description                    |
| --------------------- | ------------------------------ |
| `pnpm run build`      | Compile TypeScript to dist/    |
| `pnpm run dev`        | Run code with tsx (no compile) |
| `pnpm start`          | Run compiled JavaScript        |
| `pnpm run watch`      | Watch mode - auto recompile    |
| `pnpm run clean`      | Remove dist/ directory         |
| `pnpm run lint`       | Lint code with ESLint          |
| `pnpm run lint:fix`   | Lint and fix issues            |
| `pnpm run format`     | Format code with Prettier      |
| `pnpm run type-check` | Check types without emitting   |

## Project Structure

```
├── src/                  # Source TypeScript files
│   └── index.ts
├── dist/                 # Compiled JavaScript (generated)
├── tsconfig.json         # TypeScript configuration
├── eslint.config.mjs     # ESLint configuration (v9)
├── .prettierrc            # Prettier configuration
└── .vscode/
    └── settings.json     # VS Code settings
```

## Technology Stack

- **TypeScript 5.4** - Latest TypeScript
- **ESLint 9** - Modern linting
- **Prettier 3** - Code formatter
- **tsx 4** - Fast TypeScript executor
- **Node.js ES modules** - Modern module system

## Configuration

### TypeScript (tsconfig.json)

- Target: ES2024
- Module: ESNext
- Strict mode enabled
- Module resolution: bundler
- Source maps and declarations

### ESLint (eslint.config.mjs)

- Strict TypeScript rules
- ES2024 support
- Recommended rules

### Prettier (.prettierrc)

- 2 spaces indentation
- Single quotes
- Trailing commas
- 80 character line width

## IDE Setup

VS Code settings are pre-configured in `.vscode/settings.json`:

- Auto-format on save
- ESLint auto-fix on save
- TypeScript strict mode
- Prettier as default formatter

## License

ISC
