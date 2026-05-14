---
layout: post
title: "About This Site"
date: 2026-05-14
description: "How and why this site is built the way it is"
---

This site is a lightweight static website hosted on GitHub Pages.

The goal is to keep publishing simple: write content in plain text, store everything in Git, and let GitHub handle the hosting. That means the entire site can be updated with normal commits, reviewed through history, and rolled back easily if needed.

## Architecture

The site uses a standard Jekyll structure:

- `_posts/` for blog posts in Markdown
- `_layouts/` for custom HTML templates
- `_config.yml` for site metadata
- `index.html` as the homepage, rendered by Jekyll with Liquid templates
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

## Content workflow

The publishing workflow is intentionally simple:

1. create or edit a file in `_posts/`
2. commit the change
3. let GitHub Pages build and publish the updated site

## Design goals

The main priorities for this site are:

- clarity over complexity
- plain-text authoring
- low maintenance
- incremental improvement
