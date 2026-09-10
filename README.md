# Code of IX

A design and UX standards framework for building consistent, accessible, and ethical intelligent experiences (IX).

## Overview

Code of IX is a shared reference for designers, developers, and product teams. It provides principles, standards, and practical techniques for creating AI-powered user interfaces that are high-quality, inclusive, and responsible.

The framework is organized into three layers:

| Layer | File | Purpose |
|---|---|---|
| **EthIX** | `ethix.md` | The *why* — ethical principles and values |
| **BasIX** | `basix.md` | The *what* — foundational standards and rules |
| **TactIX** | `tactix.md` | The *how* — practical techniques and patterns |

Start with [`code-of-ix.md`](code-of-ix.md) for an introduction and navigation guide.

## Contents

### EthIX - Ethical principles

This layer is work in progress. `ethix.md` will document responsible AI design values (transparency, user control, avoiding manipulation).

### BasIX — Foundational Standards

The most developed section, covering 92+ guidelines across 11 areas:

1. Accessibility
2. Actions and buttons
3. Content and language
4. Dialogs and overlays
5. Feedback and system status
6. Forms and validation
7. Icons and iconography
8. Interaction and motion
9. Layout and responsive design
10. Navigation and disclosure
11. Tables and data

### TactIX - Practical techniques

This layer is work in progress. `tactix.md` will cover implementation techniques such as progressive disclosure, sensible defaults, and user validation.

#### Patterns

The `patterns/` directory contains supporting visual examples of key patterns and layouts. Currently includes:

- [`patterns/tables.md`](patterns/tables.md) — When and how to use tables

## Usage

All content is written in Markdown and can be read directly in any editor or rendered via a documentation site. There is no build step required.

Browse the files directly, or use your editor's search to find guidance on a specific topic (e.g., search for `validation`, `empty state`, or `pagination`).

## Contributing

When adding or updating guidelines:

- Place foundational rules in `basix.md` under the relevant section
- Add component-specific patterns with visuals to `patterns/`
- Keep each guideline specific and actionable
