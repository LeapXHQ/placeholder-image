# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a public asset repository (`LeapXHQ/placeholder-image`) that hosts logo images used by the LeapX app. It contains no source code, build steps, or tests — only static image files served from the repo.

## Structure

Logos are organized into subdirectories by product/workspace (e.g., `harmony-logos/`, `workspaces/`). This CLAUDE.md lives in the `harmony-logos/` subdirectory.

## Image URLs

Images are served via GitHub raw URLs. The pattern is:

```
https://raw.githubusercontent.com/LeapXHQ/placeholder-image/main/<path>
```

For example: `https://raw.githubusercontent.com/LeapXHQ/placeholder-image/main/harmony-logos/logo-harmony.png`

**Caution: This is a public repository. Do not commit any sensitive or internal assets here.**

## Working with This Repo

- No build, lint, or test commands exist — changes are limited to adding, replacing, or removing image assets
- Images are referenced by URL from external applications, so **renaming or deleting existing files is a breaking change**
- When adding new logos, use a descriptive filename with the pattern `logo-<name>.png`
