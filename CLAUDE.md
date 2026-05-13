# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static HTML website for **OrbitLoop**, an AI-powered growth systems product. No build system, package manager, or dependencies — open files directly in a browser.

## Files

- `index.html` — Main marketing/landing page. All CSS and JS are inline (no external stylesheets or scripts beyond Google Fonts). Uses external `orbitloop-wordmark.svg` logo.
- `brochure.html` — Printable product guide. Uses [html2pdf.js](https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js) (loaded from CDN) to support in-browser PDF export. Styled as A4 pages with watermark and a fixed download toolbar.
- `orbitloop-wordmark.svg` — SVG wordmark logo; referenced in both HTML files.

## Design System

All design tokens are CSS custom properties defined in `:root` inside `index.html`:

| Token | Purpose |
|---|---|
| `--violet` / `--v10` / `--v20` | Primary brand color + alpha variants |
| `--green` / `--g10` | Accent / live indicator |
| `--bg`, `--surface`, `--sf2` | Page and card backgrounds |
| `--text`, `--muted`, `--faint` | Text hierarchy |
| `--r`, `--r-sm`, `--r-pill` | Border radius scale |
| `--shadow-sm` … `--shadow-lg` | Elevation scale |

`brochure.html` uses its own inline palette (no shared CSS file).
