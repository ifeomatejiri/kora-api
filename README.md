# kora-api

A lightweight API service built while practicing end-to-end Git and GitHub CLI (`gh`) workflows.

## Overview
This repository demonstrates managing issues, feature branches, pull requests, and merges directly from the command line.

## Endpoints
- **`GET /health`** — Health check route defined in `health.js` that returns `{ status: 'ok' }`.

## Workflow Practiced
- Created and linked issue `#1` to a feature branch (`add-health`).
- Opened, inspected, and verified Pull Request `#2` using `gh pr view`, `gh pr diff`, and `gh pr checks`.
- Squashed and merged the pull request into `main` with automatic branch cleanup using `gh pr merge`.
