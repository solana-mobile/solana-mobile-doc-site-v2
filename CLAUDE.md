# Context

This is a Mintlify documentation site for Solana Mobile. The site uses `docs.json` for navigation/sidebar config and `.mdx` files for content.

## Rules

- Never run `mintlify dev` after making changes. Assume a dev server is already running.
- When editing docs, always check for and update: sidebar/navigation in `docs.json`, cross-references and internal links, and any index or overview pages that reference the changed content.
- Use `get-started/` not `getting-started/` — the `getting-started/` folder is legacy/orphaned.

## Writing Style

- **Keep card/link descriptions generic and resilient.** Don't reference specific implementation details (framework names, number of methods, specific technologies) in card descriptions or link summaries. The description should remain accurate even if the underlying doc adds languages, methods, or approaches.
- **Be concise.** Prefer short, direct descriptions. One sentence per card description.
- **Use imperative/action-oriented language.** "Learn how to...", "Submit your app...", "Build and sign..." rather than passive constructions.
- **Avoid redundancy.** Don't repeat the card title in the description. The description should add context, not echo the title.
- **No over-qualification.** Don't say "two primary methods" or "React Native application" when the scope may broaden. Say "your app" instead of "your React Native app" when possible.
- **Section titles should be clean and simple.** Use short, recognizable names (e.g., "Resources", "dApp Store") over verbose ones (e.g., "Additional Resources for Building Mobile Apps").
