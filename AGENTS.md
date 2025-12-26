# Agent Guidelines for DeepTree Website

## Overview

This repository contains the static website for DeepTree (https://deeptree.com).

## Key Considerations

- **Simplicity**: This is a minimal static site. Keep changes simple and focused.
- **No build step**: Changes to HTML/CSS are deployed directly via GitHub Pages.
- **Custom domain**: The CNAME file configures the custom domain - do not modify unless intentionally changing domains.

## Making Changes

1. All visible content is in `index.html`
2. Styles are inline in the `<head>` section
3. The site uses Plausible Analytics (script in `<head>`)

## Deployment

Push to `main` branch to deploy. GitHub Pages handles the rest.

## Testing Locally

Open `index.html` directly in a browser to preview changes.
