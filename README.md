# BAMF.ai for ChatGPT and Codex

BAMF.ai connects creator workspaces to ChatGPT and Codex through a hosted MCP server and a workflow skill. Use it to review creator context, research and develop ideas, prepare drafts and media, manage connected publishing workflows, and analyze results.

The package is portable across ChatGPT and Codex. Its root `plugin.json` declares the Agent Plugins 1.0 manifest, `mcp.json` configures the hosted streamable HTTP server, and `skills/bamf-ai/SKILL.md` describes the approval-aware workflow. There is no custom app UI in this package.

## Install and connect

Add the package through a supported ChatGPT/Codex plugin marketplace or directory. Open BAMF.ai and complete the connector's sign-in and workspace authorization flow when prompted. The remote connection handles authentication; do not paste API keys or access tokens into chat or package files.

## Safe use

Read the selected creator space's context before acting. Preparing ideas and copy in chat does not save them. Confirm the exact content, target, platform, timing, and any spend controls before saving or changing workspace data, scheduling, publishing, deleting, boosting, sending, or making another external write. Report provider effects only when BAMF returns a receipt.

Media generation and media-library actions depend on the tools available to the connected account. The skill requires a clear confirmation before generation or any upload, attachment, replacement, or deletion that writes to BAMF or a provider.

## Package contents

- `plugin.json` — portable plugin identity and OpenAI presentation metadata.
- `mcp.json` — the hosted BAMF.ai MCP endpoint.
- `skills/bamf-ai/SKILL.md` — connector workflow and approval rules.
- `assets/` — BAMF.ai logo and icon copied from the public BAMF.ai package assets.

## Support and policies

- Documentation: <https://bamf.ai/docs/mcp/overview>
- Support: <https://bamf.ai/support>
- Privacy: <https://bamf.ai/privacy/>

See `LICENSE` for package terms.
