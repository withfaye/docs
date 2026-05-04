# Documentation project instructions

## About this project

- This is a Mintlify documentation site for the Faye Partner Sales API.
- Pages are MDX files with YAML frontmatter.
- Configuration lives in `docs.json`.
- Run `mint dev` to preview locally.
- Run `mint broken-links` to check links.

## Terminology

- Use "partner" for the business integrating with Faye.
- Use "traveler" for the covered customer.
- Use "advisor" for licensed travel advisors under a partner account.
- Use "quote hash" for `quoteHash` and "group hash" for `groupHash`.
- Use "policy" for purchased coverage.
- Use "payment token" for provider-generated card tokens.

## Style preferences

- Use active voice and second person.
- Keep sentences concise.
- Use sentence case for headings.
- Bold UI elements: Click **Settings**.
- Code format file names, commands, endpoints, paths, and field names.
- Prefer V2 quote and purchase endpoints for new integrations.

## Content boundaries

- Document partner-facing API behavior only.
- Do not document internal Faye admin tools.
- Do not include real bearer tokens, card numbers, CVV values, or production payment credentials.
- Use the OpenAPI spec as the source of truth for request and response schemas.
