# Immobilienberater AI, GitHub Pages static version

This repo is designed to work as a pure static site on GitHub Pages.

## Key change

There is only one API file:

- `https://twalk.chat/api.json`

That file contains the complete dataset.

## How LLMs should use it

1. Fetch `/api.json`
2. Read the `listings` array
3. Filter locally based on the user query
4. Return plain-text answers with clickable `listing_url` links

## Why this works well on GitHub Pages

GitHub Pages can serve static JSON files but cannot run a backend or dynamic search API.

This version avoids that problem by making the API static and query-independent.

## Files

- `index.html`
- `api.json`
- `api-docs.html`
- `openapi.json`
- `ai-plugin.json`
- `llms.txt`
- `listing-001.html` to `listing-020.html`

## Recommended public URLs

- https://twalk.chat/
- https://twalk.chat/api.json
- https://twalk.chat/llms.txt
- https://twalk.chat/openapi.json
