# CLAUDE.md — AI Assistant Guide

## Project Overview

**design4mydog-produktseite** is a product presentation website for DESIGN4MYDOG dog feeding stations. It showcases three wood types (Bambus/Bamboo, Buche/Beech, Eiche/Oak) with size comparisons and detailed product information. The site is in German.

## Repository State

This repository is in its **initial setup phase** — it currently contains only this guide and a README. No framework, build tooling, or source code has been committed yet.

## Project Structure

```
/
├── README.md        # Project description (German)
├── CLAUDE.md        # This file — AI assistant guide
└── .git/            # Git repository
```

## Development Conventions

### Language & Content
- All user-facing content is in **German**
- Code comments and commit messages should be in **English**
- Variable/function names should be in **English**

### Git Workflow
- **Main branch:** `main`
- Feature branches should be prefixed with the contributor name or purpose
- Commit messages: concise, imperative mood, English (e.g., "Add product card component")
- Do not commit secrets, `.env` files, or build artifacts

### Recommended .gitignore entries (when code is added)
```
node_modules/
dist/
.env
.env.local
*.log
.DS_Store
```

## Build & Dev Commands

_No build system configured yet._ When a framework is chosen, update this section with:
- Install command (e.g., `npm install`)
- Dev server command (e.g., `npm run dev`)
- Build command (e.g., `npm run build`)
- Test command (e.g., `npm test`)
- Lint command (e.g., `npm run lint`)

## Testing

_No test infrastructure configured yet._ Update this section when tests are added.

## Key Domain Concepts

| German Term | English | Description |
|---|---|---|
| Futterstation | Feeding station | The core product — elevated dog bowl stands |
| Bambus | Bamboo | Wood type option |
| Buche | Beech | Wood type option |
| Eiche | Oak | Wood type option |
| Größenvergleich | Size comparison | Feature showing product dimensions relative to dog sizes |
| Produktinformationen | Product information | Detailed specs and descriptions |

## Notes for AI Assistants

- This is a **product showcase site**, not an e-commerce platform (no cart/checkout unless explicitly requested)
- When adding components, keep accessibility in mind (`alt` text in German, semantic HTML)
- Optimize images for web — product photography is central to this site
- Responsive design is expected (mobile-first approach recommended)
- Keep the design clean and professional — this represents a premium pet product brand
