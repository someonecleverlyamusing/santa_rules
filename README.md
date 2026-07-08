# Santa Rules

Test repository for managing Santa static rules.

## Purpose

This repository stores Santa rule JSON files for testing GitHub-based Santa rule management before moving to an organization-owned production repository.

## Current files

- `rules/santa-rules.json` - Main Santa static rules file
- `scripts/` - Future endpoint sync scripts
- `docs/` - Notes and deployment documentation

## Test rule

The initial test rule blocks Apple Chess using its signing ID:

```json
platform:com.apple.Chess
