# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

GitHub Pages site for DK Bielany Toruń, hosted at `dk-bielany-torun.github.io`.

## Repository

- **Remote**: `git@github.com:dk-bielany-torun/dk-bielany-torun.github.io.git`
- **Branch**: `main` (deploys automatically via GitHub Pages)
- **Language**: Polish (content is in Polish)

## Tech Stack

- **Jekyll** static site generator (v4.3)
- Custom theme with dark gray + gold accent color scheme
- **Simple-Jekyll-Search** for client-side search
- **GitHub Pages** for hosting and deployment

## Build & Dev Commands

```bash
bundle install              # Install dependencies
bundle exec jekyll serve    # Dev server at localhost:4000
bundle exec jekyll build    # Production build to _site/
```

## Post Tags

Posts use tags in front matter: `bielany`, `wrzosy`, or `oba` (both parishes).
Use `pinned: true` in front matter to pin a post to the top of the homepage.
