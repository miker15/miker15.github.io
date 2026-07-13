# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Personal portfolio/landing page for https://michaelrichterswe.com, hosted via GitHub Pages (custom domain configured in `CNAME`). Plain HTML/CSS with no frameworks or CDN dependencies — social icons are inlined as SVG rather than pulled from an icon font. No build tooling, package manager, or test suite.

## Development

There is no build/lint/test process. Edit `index.html` and `css/style.css` directly and open `index.html` in a browser to preview changes. Deployment is automatic via GitHub Pages on push to the default branch.

## Structure

- `index.html` — the single page; content, meta/OpenGraph tags, and inline SVG icons (LinkedIn, GitHub, resume, email) live here.
- `css/style.css` — all styling: flexbox centering, a dark gradient background, and `clamp()`-based fluid sizing so the layout scales from mobile to large monitors without media-query breakpoints.
- `images/` — favicon, profile photo, and README preview image.
- `resume/Resume.pdf` — resume linked from the page.
- `CNAME` — GitHub Pages custom domain config; do not remove unless intentionally changing the domain.
