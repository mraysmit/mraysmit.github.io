# About This Site

This site is a lightweight static website hosted on GitHub Pages.

The goal is to keep publishing simple: write content in plain text, store everything in Git, and let GitHub handle the hosting. That means the entire site can be updated with normal commits, reviewed through history, and rolled back easily if needed.

## Architecture

The site currently uses a minimal structure:

- `index.html` for the homepage
- Markdown files for post content
- a GitHub repository as the source of truth
- GitHub Pages for build and hosting

This approach keeps the stack small and easy to maintain. There is no separate database, CMS, or deployment pipeline to manage.

## Why this setup

A static site has a few advantages:

- low operational complexity
- fast page loads
- version-controlled content
- simple deployment model
- easy portability

Because the site content lives alongside the code, edits are transparent and traceable. Every change has a commit history, and restoring a previous version is straightforward.
