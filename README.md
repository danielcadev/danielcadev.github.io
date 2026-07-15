# Daniel Castrillon Portfolio

Technical portfolio focused on production platform engineering, application security, open-source work, and evidence-backed engineering outcomes.

## Stack

- Astro 7 and TypeScript
- Tailwind CSS 4 through the official Vite plugin
- Lucide icons for Astro
- Self-hosted Manrope and IBM Plex Mono fonts
- Static output with no client framework

## Commands

```bash
pnpm install
pnpm dev
pnpm check
pnpm build
pnpm preview
```

## Structure

```text
src/
  components/   Shared header and project case components
  layouts/      Document shell, metadata, fonts, and theme setup
  pages/        Portfolio routes
  styles/       Tailwind entry point and design tokens
public/
  images/       Real production product captures
```

## Content

The main portfolio content lives in `src/pages/index.astro`. Project screenshots are intentionally stored locally so the portfolio remains stable if a production homepage changes.

The codebase-scale figure links to the public measurement methodology in the `danielcadev/danielcadev` profile repository. It should only be updated alongside a new reproducible audit.
