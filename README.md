# My Frontend

Simple Nuxt frontend project for learning GitHub Actions CI.

## Run locally

```bash
pnpm install
pnpm run dev
```

Open http://localhost:3000

## Build

```bash
pnpm run build
```

## GitHub Actions

The workflow is located at:

`.github/workflows/ci.yml`

It runs when code is pushed to the `main` branch or when a pull request targets `main`.
