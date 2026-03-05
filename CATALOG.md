# Template Catalog

A quick reference for every CLAUDE.md template in this repo. Pick the one that matches your stack, copy it to your project root, and replace the `[PLACEHOLDERS]`.

| Template | Stack | Key Libraries | Lines | Last Updated |
|----------|-------|---------------|-------|--------------|
| [nextjs](templates/nextjs/CLAUDE.md) | Next.js 14+ App Router, TypeScript | Tailwind, Prisma, Zod, date-fns, TanStack Query | 84 | 2026-03-05 |
| [react-vite](templates/react-vite/CLAUDE.md) | React 18, TypeScript, Vite | TanStack Query, Zustand, Tailwind, react-hook-form | 82 | 2026-03-05 |
| [python-fastapi](templates/python-fastapi/CLAUDE.md) | Python 3.11+, FastAPI | SQLAlchemy 2.0, Pydantic v2, Alembic, passlib | 88 | 2026-03-05 |
| [flutter](templates/flutter/CLAUDE.md) | Flutter 3.x, Dart 3.x | Riverpod, GoRouter, Freezed, Dio, mocktail | 91 | 2026-03-05 |
| [saas-fullstack](templates/saas-fullstack/CLAUDE.md) | Next.js 14, TypeScript | Prisma, Stripe, Clerk/Auth.js, Resend, React Email | 96 | 2026-03-05 |
| [monorepo](templates/monorepo/CLAUDE.md) | Turborepo, pnpm workspaces | TypeScript, shared packages, Vitest | 109 | 2026-03-05 |
| [ml-python](templates/ml-python/CLAUDE.md) | Python 3.11+, ML/Data Science | PyTorch, scikit-learn, MLflow, polars, FastAPI | 113 | 2026-03-05 |
| [open-source-lib](templates/open-source-lib/CLAUDE.md) | TypeScript library | Vitest, tsup, Changesets, GitHub Actions | 119 | 2026-03-05 |
| [django](templates/django/CLAUDE.md) | Python 3.11+, Django 5.x, DRF | Celery, Redis, django-allauth, pytest-django | 98 | 2026-03-05 |
| [express-typescript](templates/express-typescript/CLAUDE.md) | Node.js 20+, Express 4.x, TypeScript | Prisma, Zod, Pino, jose (JWT), supertest | 91 | 2026-03-05 |
| [go-api](templates/go-api/CLAUDE.md) | Go 1.22+, Chi router | sqlc, pgx, slog, goose, testcontainers-go | 89 | 2026-03-05 |
| [react-native-expo](templates/react-native-expo/CLAUDE.md) | React Native 0.73+, Expo SDK 50+ | Expo Router, TanStack Query, Zustand, SecureStore | 86 | 2026-03-05 |
| [sveltekit](templates/sveltekit/CLAUDE.md) | SvelteKit 2.x, Svelte 5 (runes) | Tailwind, Drizzle ORM, Lucia, superforms, Zod | 85 | 2026-03-05 |
| [nuxt](templates/nuxt/CLAUDE.md) | Nuxt 3.x, Vue 3, Composition API | Pinia, Tailwind, Zod, VeeValidate, Nitro | 91 | 2026-03-05 |
| [chrome-extension](templates/chrome-extension/CLAUDE.md) | Chrome Extension MV3, TypeScript | Vite, CRXJS, React, chrome.storage, contextBridge | 84 | 2026-03-05 |
| [cli-node](templates/cli-node/CLAUDE.md) | Node.js 20+, TypeScript | Commander, Chalk, Ora, Inquirer, tsup, execa | 83 | 2026-03-05 |
| [astro](templates/astro/CLAUDE.md) | Astro 4.x, TypeScript | Content Collections, MDX, Tailwind, Pagefind, Playwright | 95 | 2026-03-05 |
| [rust-axum](templates/rust-axum/CLAUDE.md) | Rust (stable), Axum 0.7+ | SQLx, Tokio, Tower, serde, thiserror, tracing | 85 | 2026-03-05 |
| [electron](templates/electron/CLAUDE.md) | Electron 28+, React 18, TypeScript | Vite, electron-builder, electron-updater, Zustand | 87 | 2026-03-05 |
| [laravel](templates/laravel/CLAUDE.md) | PHP 8.2+, Laravel 11 | Eloquent, Sanctum, Filament, Pest, Laravel Horizon | 94 | 2026-03-05 |

---

## Community Templates

*No community templates yet.* Want to add one?

1. Read the [Contributing Guide](CONTRIBUTING.md)
2. Create a new directory under `templates/` with your stack name
3. Write a `CLAUDE.md` following the template structure requirements (80–150 lines, opinionated, stack-specific)
4. Run `python scripts/validate.py` to make sure it passes
5. Open a PR — community templates will be listed in this section

<!-- COMMUNITY_TEMPLATES_START -->
<!-- Add community templates here via PR. Format: -->
<!-- | [template-name](templates/template-name/CLAUDE.md) | Stack description | Key Libraries | ~lines | YYYY-MM-DD | -->
<!-- COMMUNITY_TEMPLATES_END -->
