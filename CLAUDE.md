# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static website for Jade Medical Aesthetics, a medical aesthetics clinic. Hosted via GitHub Pages from the `docs/` directory, served at `jademedicalaesthetics.co.uk`.

## Architecture

- **Single-page static site** — all content lives in `docs/index.html` (HTML + inline CSS, no build step)
- **`docs/`** — GitHub Pages root; contains `index.html`, `CNAME`, and image assets
- **No build tools, no JavaScript, no package manager** — edit HTML/CSS directly

## Deployment

Pushing to `main` deploys automatically via GitHub Pages. The `docs/` folder is the publish source.

## Design Tokens

- **Brand green:** `#2d5a4c` (headings, buttons, footer background)
- **Gold/tan palette:** `#d4c5a9`, `#e8dcc8`, `#d9cab2`, `#f0e8d8` (header gradient, accents)
- **Heading font:** Cormorant Garamond (Google Fonts)
- **Nav/UI font:** Montserrat (Google Fonts)
- **Body font:** system font stack
