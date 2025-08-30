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
This repository follows standard Jekyll conventions:
- `_config.yml` - Jekyll configuration
- `_posts/` - Blog posts in Markdown format
- `_layouts/` - HTML templates
- `_includes/` - Reusable template components
- `assets/` - CSS, JavaScript, and images
- `index.md` - Homepage

## Content Guidelines
- **Prefer Markdown over HTML**: When creating new content for the site, use Markdown format (`.md` files) rather than HTML when possible
- Jekyll will automatically convert Markdown to HTML during the build process
- Use HTML only when Markdown limitations require it (complex layouts, specific styling needs, etc.)

## Notes
- The `.gitignore` is configured for Jekyll with entries for `_site/`, `.sass-cache/`, `.jekyll-cache/`, and `.bundle/`
- Repository uses the `main` branch as the primary branch