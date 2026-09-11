> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is the help/docs site for [Matchr](https://matchr.in), a Chrome extension + web dashboard that scores a resume against LinkedIn job postings in real time and offers a chat-based resume optimizer.
- Built on [Mintlify](https://mintlify.com). Pages are MDX files with YAML frontmatter. Configuration lives in `docs.json`.
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP.
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP.

## Terminology

- "The extension" or "the side panel" = the Chrome extension's UI on LinkedIn job pages. Not "the app" or "the widget".
- "The dashboard" = the web app at matchr.in. Not "the portal" or "the website" when referring to the logged-in product area.
- "Match" or "job match" = one scored resume-against-job-posting pairing. Not "analysis" or "scan" in user-facing copy, though "scoring"/"analyzing a job" is fine as a verb.
- "The resume optimizer" = the chat-based resume-editing feature, always capitalized as a feature name when referenced directly: "Optimize My Resume" is the literal button label.
- "Credits" = the single spendable currency across the product. Never call them "tokens" or "points".
- "Plan" = Free Trial, 7-Day Sprint, or 30-Day Pass. These are one-time purchases, not subscriptions, never call them "subscriptions" or say a plan "renews".

## Style preferences

- Use active voice and second person ("you").
- Keep sentences concise, one idea per sentence.
- Use sentence case for headings.
- Bold for UI elements: click **Settings**.
- Code formatting for file names, commands, paths, and code references.
- Never invent numbers, thresholds, or behavior that isn't confirmed against the actual product. If unsure, say less rather than guess.
- No em dashes (—). Use a comma, period, or parentheses instead.

## Content boundaries

- This site documents end-user, product-facing behavior only: the extension, the dashboard, plans/credits, and the resume optimizer.
- Don't document internal implementation details (backend architecture, database schema, admin-only tooling) or anything gated to the `jobs.matchr@gmail.com` admin account.
- Don't state legal specifics about data handling, privacy, or terms, link to the real Privacy Policy (`https://matchr.in/privacy`) and Terms (`https://matchr.in/terms`) instead of restating them.
