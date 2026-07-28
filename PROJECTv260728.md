# PROJECT.md

# CS3C Website

## Project Status

**Status:** Active

**Current phase:** Sprint 6 — Capability Model

Repository:

https://github.com/CS3C-ORG/CS3C-Website

Live website:

https://cs3c.netlify.app

Latest public milestone:

**M1 — Public Foundation completed ✅**

# Vision

Build a modern, engineering-first cybersecurity knowledge platform.

The website is not intended to be a traditional consulting company website.

Its primary purpose is to present:

- research
- methodologies
- engineering models
- technical publications
- practical tools

Knowledge is the product.

# Current Sprint

## Sprint 6 — Capability Model

### Goal

Create the first substantive CS3C model page and begin filling the platform with real engineering knowledge.

### Planned Tasks

- define the Capability Model page architecture
- explain the purpose and scope of the model
- define the initial model structure
- introduce capability domains and capability areas
- define maturity, dependencies, metrics, and implementation guidance
- create the first visual representation of the model
- connect homepage navigation to the new page

# Completed

## Sprint 1

- Repository initialized
- GitHub repository created
- Vision defined
- Information Architecture completed
- ADR-0001 created
- Home Wireframe v1 completed

## Sprint 2

- Design Manifesto created
- Design System v1 created
- Brand personality defined
- Typography selected
- Color palette selected
- Engineering Minimalism established

## Sprint 3

- Astro project created
- Tailwind CSS v4 integrated
- Project structure finalized
- Static build configured

## Sprint 4

- reusable UI components
- Header and Footer
- MainLayout and SiteLayout
- metadata support
- responsive foundation
- production build
- GitHub synchronization

## Sprint 5

### Brand

- Official CS3C Brand Mark adopted
- Five-layer master geometry defined
- SVG brand assets created
- Brand specification approved
- ADR-0002 created
- Official favicon integrated

### Homepage

- Hero
- Why CS3C Exists
- CS3C Knowledge System
- Models
- Publications
- About CS3C
- responsive desktop and mobile layouts
- Header and Footer navigation
- homepage visual polish

### Publication

- repository published under CS3C-ORG
- Netlify deployment configured
- automated deployments from `main`
- public website launched
- first public GitHub release created

# Current Architecture

```text
MainLayout
└── HTML document
    └── SiteLayout
        ├── Header
        ├── Main
        │   └── Homepage sections
        └── Footer
```

## UI Components

- Container
- Section
- Heading
- Text
- Button
- Logo

## Homepage Components

- Hero
- WhyCS3C
- KnowledgeSystem
- Models
- Publications
- AboutCS3C

# Key Decisions

- Content first
- Engineering before marketing
- Platform before website
- Knowledge is the product
- Engineering Minimalism
- Evidence. Engineered.
- Forest Green accent
- Inter typeface
- Astro
- Tailwind CSS v4
- Static-first architecture
- SVG-first visual identity
- Publications, not a blog
- Capability Model as the first substantive model
- GitHub as the source repository
- Netlify for continuous deployment

# Roadmap

## Milestone M1 — Public Foundation ✅

- visual identity
- homepage
- responsive design
- GitHub repository
- Netlify deployment
- first public release

## Milestone M2 — Capability Model 🚧

- model architecture
- model content
- visual model representation
- dedicated model page

## Milestone M3 — Publications Library

- White Papers
- Technical Notes
- Specifications
- Reference Guides

## Milestone M4 — Workbench

- product overview
- architecture
- workflows
- documentation

# Session Resume

When resuming this project:

1. Read `PROJECT.md`.
2. Continue from the current sprint.
3. Do not redesign accepted decisions unless explicitly requested.
4. Treat the `/docs` directory as the source of truth.
5. Preserve the approved CS3C Brand Mark v1.0.
6. Keep the homepage stable unless a specific change is requested.

## Changelog

### 2026-07-28

Sprint 5 completed.

The production homepage was completed and published.

Official CS3C visual identity and favicon were integrated.

The website was deployed to Netlify with automated deployments from GitHub.

The first public release was created.

Sprint 6 begins with the Capability Model.

### 2026-07-27

Sprint 4 completed.

Website foundation finished.

Reusable design system implemented.

Reusable layouts implemented.

Homepage implementation started in Sprint 5.

## Source of Truth

`PROJECT.md` is the entry point for this repository.

Avoid duplicating documentation.

Extend documentation only when it provides long-term value.
