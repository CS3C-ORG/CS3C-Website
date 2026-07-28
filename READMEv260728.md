# CS3C Website

Official website of the CS3C Engineering Knowledge System.

- Live website: https://cs3c.netlify.app
- Repository: https://github.com/CS3C-ORG/CS3C-Website

## Technology

- Astro
- Tailwind CSS v4
- Netlify

## Current Status

✅ **Milestone M1 — Public Foundation completed**

The first public version of the CS3C website is live.

Implemented:

- reusable design system and layouts
- responsive desktop and mobile experience
- metadata and production build
- official CS3C visual identity and favicon
- complete production homepage
- working internal navigation
- automated Netlify deployment from GitHub
- first public GitHub release

The next milestone is the **Capability Model**.

## Homepage

The production homepage includes:

- Hero
- Why CS3C Exists
- CS3C Knowledge System
- Models
- Publications
- About CS3C
- Header and Footer navigation

## Project Structure

```text
website/
└── src/
    ├── components/
    │   ├── home/
    │   ├── layout/
    │   └── ui/
    ├── layouts/
    ├── pages/
    └── styles/
```

Brand assets and specifications are stored in:

```text
assets/
└── logo/
```

Architecture and design decisions are stored in:

```text
docs/
├── adr/
└── wireframes/
```

## Development

```bash
cd website
npm install
npm run dev
npm run build
npm run preview
```

On Windows, the equivalent commands may be run with `npm.cmd`.

## Deployment

```text
Branch: main
Base directory: website
Build command: npm run build
Publish directory: dist
```

Every push to `main` triggers an automatic production deployment.

## Current Milestone

**M2 — Capability Model**

The next development phase focuses on creating the first substantive CS3C model page and expanding the platform with real engineering knowledge.
