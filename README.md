# Ijtihad Labs Hub

This repository powers the Ijtihad Labs hub site at https://ijtihadlabs.org.

## Purpose

The hub lists Ijtihad Labs tools in one place, reflecting a privacy-first,
charity-driven ethos with humble, service-oriented language.

## Local preview

```bash
python3 -m http.server 5174
```

Open: http://127.0.0.1:5174

## Deployment

This is a static site deployed on Netlify.

- Publish directory: `.`
- Build command: none

DNS points the root domain to Netlify and `www` CNAMEs to the Netlify site.

## Repository

- `index.html` for the hub landing page
- `apps/` for app detail pages
- `assets/` for styles and shared imagery
