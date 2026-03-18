# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links
- The primary docs audience is marketers, operators, and technical users connecting to the Outfox MCP suite

## Terminology

- Use **organization** for the top-level Clerk and Outfox workspace
- Use **brand** for an Outfox brand profile inside an organization
- Use **inspiration library** for the ad corpus users search
- Use **Meta analytics** for campaign, ad set, ad, and creative performance data
- Use **MCP client** for Claude, Cursor, or any other tool connecting to `https://app.outfox.ai/api/mcp`

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Lead with the user outcome before the implementation detail
- Be explicit about whether a page describes a live workflow or a broader suite
- Prefer concrete prompts over abstract tool descriptions

## Content boundaries

- Document public MCP usage, OAuth setup, workflows, prompts, and docs deployment
- Do not document internal admin-only systems unless they affect end-user setup
