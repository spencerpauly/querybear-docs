# QueryBear Docs

Public documentation for [QueryBear](https://querybear.com) — a secure, read-only MCP server for PostgreSQL, MySQL, and SQLite. Built on [Mintlify](https://mintlify.com).

Deployed to **docs.querybear.com**.

> Source of truth: this repo. The main app lives in the private `spencerpauly/querybear` monorepo; docs were split out here so the free Mintlify tier (public repo) can host them.

## Structure

- `docs.json` — site config (theme, navigation, branding)
- `index.mdx` — introduction / landing
- `what-is-mcp.mdx`, `quickstart.mdx`, `security.mdx` — top-level pages
- `databases/` — per-database guides (Postgres, MySQL, SQLite)
- `clients/` — per-AI-client guides (Claude Code, Claude Desktop, Cursor, Codex, Windsurf, ChatGPT)
- `guides/` — the database × client setup matrix (18 pages)

## Local preview

Install the Mintlify CLI and run from the repo root:

```bash
npm i -g mint
mint dev
```

Preview at `http://localhost:3000`.

## Publishing

The Mintlify GitHub app watches this repo. Pushes to `main` deploy automatically to docs.querybear.com.

## TODO

- Replace the placeholder Mintlify logos in `logo/` and `favicon.svg` with QueryBear branding.
