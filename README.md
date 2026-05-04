# Faye Partner Documentation

This is the Mintlify documentation site for partners integrating with the Faye Partner Sales API.

The site documents how to:

- Authenticate with Faye-issued bearer tokens.
- Generate single-product and multi-product quotes.
- Tokenize credit cards with an approved payment provider.
- Purchase policies through the V2 purchase flow.
- Manage advisors, policies, amendments, cancellations, and common validation errors.

## Local preview

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the preview server from this directory:

```bash
mint dev
```

The local preview opens at `http://localhost:3000`.

## Link checks

Run:

```bash
mint broken-links
```

## Source material

- `api-reference/openapi.yaml` is the live OpenAPI reference.
- `Faye API Documentation.pdf` contains partner policy rules, state differences, and common error messages.
- `docs.json` controls Mintlify navigation and site configuration.
