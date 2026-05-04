# Contribute to the documentation

Use this guide when updating the Faye Partner Documentation site.

## Local development

1. Install the Mintlify CLI: `npm i -g mint`.
2. Run `mint dev` from this directory.
3. Preview changes at `http://localhost:3000`.
4. Run `mint broken-links` before publishing when the CLI is available.

## Writing guidelines

- Use active voice and second person.
- Keep sentences concise.
- Use sentence case for headings.
- Format endpoints, fields, commands, and file paths as code.
- Bold UI labels when you reference interface text.
- Prefer the current V2 quote and purchase flow for new integrations.
- Use the OpenAPI spec as the source of truth for endpoint schemas.

## Content boundaries

- Document partner-facing API behavior only.
- Do not document internal Faye admin workflows.
- Do not include raw card numbers, CVV values, real bearer tokens, or production payment credentials.
- Use staging-safe placeholders in examples.
