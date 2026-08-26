> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise: one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}

## PolyFundr Mission Control

- Company strategy, product, marketing, user, competitor, partnership, fundraising, metric, and risk context lives in the private repository `Samanimkr/polyfundr-mission-control` on branch `master`.
- In remote chats, use the GitHub MCP connector as the live source of truth. Fetch and follow `AI-INSTRUCTIONS.md` from that repository before using Mission Control context.
- When working locally, the vault is normally available at `~/mission-control`; read its current files directly instead of relying on remembered chat context.
- Read only the dashboard, relevant indexes, and notes needed for the documentation task. Do not scan the whole vault.
- Mission Control is internal context, not automatically approved public copy. Never publish confidential, personal, investor-only, user-identifying, speculative, or unverified information from it.
- Check claims against the product implementation and approved public policy before publishing. Flag conflicts instead of silently choosing one source.
- Do not update Mission Control unless the user asks. When asked, make a focused Markdown change, verify the commit or local edit, and report the changed paths.
- Never access, recreate, or commit anything from `PRIVATE_DO_NOT_SYNC/`.
