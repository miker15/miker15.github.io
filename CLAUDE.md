# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Personal portfolio/landing page for https://michaelrichterswe.com, hosted via GitHub Pages (custom domain configured in `CNAME`). Plain HTML/CSS/JavaScript using Bootstrap 3.3.7 and Font Awesome 5.6.3, both loaded from CDN — no build tooling, package manager, or test suite.

## Development

There is no build/lint/test process. Edit `index.html` and `css/style.css` directly and open `index.html` in a browser to preview changes. Deployment is automatic via GitHub Pages on push to the default branch.

## Structure

- `index.html` — the single page; content, meta/OpenGraph tags, and CDN links for Bootstrap/Font Awesome live here.
- `css/style.css` — custom styling layered on top of Bootstrap (centering, background, footer positioning).
- `images/` — background, favicon, profile photo, and README preview image.
- `resume/Resume.pdf` — resume linked from the page.
- `CNAME` — GitHub Pages custom domain config; do not remove unless intentionally changing the domain.
