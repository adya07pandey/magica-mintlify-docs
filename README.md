# Magica Mintlify Docs

This folder is a Mintlify-ready documentation project for the Magica public API.

## Files

- `docs.json`: Mintlify site configuration and navigation.
- `openapi.json`: OpenAPI 3.1 API reference.
- `*.mdx`: Human-readable guides for setup, authentication, tools, architecture, webhooks, and errors.

## Local Preview

Install the Mintlify CLI:

```bash
npm i -g mintlify
```

Run the docs locally from this folder:

```bash
mintlify dev
```

## Deployment

Create a separate docs repository, for example `magica-docs`, and push the contents of this folder to that repository. Connect the repository in Mintlify, deploy it, and paste the final docs URL into the frontend and backend READMEs before submission.

Before deploying, replace placeholder production URLs in `openapi.json` with the final backend URL.
