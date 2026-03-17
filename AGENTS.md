# Edge Documentation

## About this project

Edge API documentation built on [Mintlify](https://mintlify.com). Pages are MDX files with YAML frontmatter.

- **Config**: `docs.json`
- **Preview**: `npx mint dev` (port 3000)
- **Validate**: `npx mint broken-links`

## Structure

- `index.mdx` — Home page
- `quickstart.mdx` — Getting started guide
- `authentication.mdx` — API key auth
- `credits.mdx` — Credit-based pricing
- `errors.mdx` — Error codes and formats
- `api-reference/` — All API endpoint docs (IBAN, sanctions, FX, bank, CR, country, email, phone)
- `dashboard/` — Dashboard feature guides (overview, API keys, playground, team, billing)

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Include code examples in cURL, Python, and JavaScript
- Note credit cost at the top of every endpoint page using `<Info>**Credits:** X per call</Info>`
