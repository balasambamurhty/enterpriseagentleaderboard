# Enterprise AI Agent Leaderboard

A polished, static React application for comparing enterprise AI-agent platforms by an opinionated benchmark index.

## Features

- Ranked agent leaderboard with searchable vendor/model names
- Sortable benchmark dimensions: overall score, reliability, governance, tool use, and efficiency
- Deployment filters
- Selectable detail panel with metric bars and capability tags
- Transparent high-level scoring weights
- Responsive layout for desktop and mobile

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to GitHub Pages

This repository includes a GitHub Actions workflow. In GitHub, go to **Settings → Pages**, select **GitHub Actions** as the source, then push to `main`. The published site will be available from the repository's GitHub Pages URL.

## Important note

The included scores and descriptions are illustrative seed data rather than independently validated measurements. Replace the `agents` array in `src/main.jsx` with a documented evaluation dataset before publishing the leaderboard as a research product.