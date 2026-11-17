# Shrooms notes

React, TypeScript, and Vite app. This document explains how to run it locally.

## Requirements

- Node.js 24 (see `.nvmrc`)
- pnpm 12 (see `packageManager` in `package.json`)

## Run locally

Select the Node.js version and enable pnpm:

```bash
nvm use
corepack enable
```

Install dependencies:

```bash
pnpm install
```

Start the dev server:

```bash
pnpm dev
```

Open <http://localhost:5173/shrooms_notes/>.

## Scripts

| Command        | Description                                   |
| -------------- | --------------------------------------------- |
| `pnpm dev`     | Start the dev server with hot reload          |
| `pnpm build`   | Type-check and build for production in `dist` |
| `pnpm preview` | Serve the production build locally            |
| `pnpm lint`    | Run ESLint                                    |
