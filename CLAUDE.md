# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Type
This is a GitHub Pages repository (`continuumNought.github.io`) configured for Jekyll static site generation.

## Development Setup
Since this is a Jekyll-based GitHub Pages site, typical development commands would include:
- `bundle install` - Install Jekyll and dependencies
- `bundle exec jekyll serve` - Run local development server
- `bundle exec jekyll build` - Build the site for production

## Architecture
This repository is currently in its initial state with minimal content. When content is added, it will likely follow standard Jekyll conventions:
- `_config.yml` - Jekyll configuration
- `_posts/` - Blog posts in Markdown format
- `_layouts/` - HTML templates
- `_includes/` - Reusable template components
- `assets/` - CSS, JavaScript, and images
- `index.html` or `index.md` - Homepage

## Notes
- The `.gitignore` is configured for Jekyll with entries for `_site/`, `.sass-cache/`, `.jekyll-cache/`, and `.bundle/`
- Repository uses the `main` branch as the primary branch