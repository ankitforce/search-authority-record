# Search Authority Record

A compact, vendor-neutral kit for documenting what an AI agent may search, cite, and do with current web results.

Canonical article: [Web Search Is an Authority Problem, Not Just a Retrieval Feature](https://ankitkumar3514.substack.com/p/web-search-authority-record)

## Start here

1. Read `checklists/search-authority-review.md`.
2. Copy `templates/search-authority-record.example.json`.
3. Validate a record against `schemas/search-authority-record.schema.json`.
4. Give an agent the scoped task in `agent/tasks.md`.

## What this includes

- A review checklist for a web-connected agent workflow.
- A JSON schema and example for a searchable, reviewable authority record.
- Agent instructions that keep source collection separate from factual verification and external action.

## What it intentionally excludes

This is not an implementation of a search API, a security certification, or proof that a retrieved fact is correct. It does not grant permissions, handle credentials, or replace domain-specific legal, procurement, or security review.

## License

MIT. See `LICENSE.md`.
