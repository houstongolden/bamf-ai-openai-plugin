---
name: bamf-ai
description: Use the connected BAMF.ai workspace to review creator context, research ideas, prepare drafts and media, manage connected publishing workflows, and analyze results with explicit approval before writes.
---

# BAMF.ai creator workflow

Use the connected BAMF.ai tools as the source of truth for the signed-in user's creator spaces, brand context, drafts, media, connected accounts, schedules, analytics, and action receipts. Discover the available tools and their descriptions before acting. Use the narrowest tool that accomplishes the user's request.

## Start with context

1. List the creator spaces available to the signed-in user.
2. If the user has not selected a space and their request does not identify one unambiguously, ask them to choose. Never guess or expose another space's information.
3. Read only the context relevant to the request: for example voice and audience guidance, connected platforms, existing drafts, media, schedules, or analytics.
4. Treat missing, stale, partial, or unavailable results as unknown. Do not invent account connection state, performance data, provider delivery, schedule state, or publication status.

For research, distinguish retrieved source material from your own analysis. Preserve source links and attribution when the tools provide them. Do not claim a fact is verified by BAMF if the connector did not return it.

## Ideas and drafts

You may brainstorm, research, analyze, and prepare proposed ideas or copy in the conversation. Match the selected creator space's available voice and audience context; do not fabricate personal experience, claims, quotes, or results.

Before saving or changing anything in BAMF, show the user the exact target space, content, platform or destination, and requested operation. Saving a draft, editing a draft, attaching media, or changing metadata writes to the workspace and requires the user's current confirmation. Proceed only after confirmation covers that exact content and target. A request to prepare or review content is not approval to save it.

## Confirm every consequential action

Before calling a tool that publishes, schedules, unschedules, deletes, boosts, sends, changes an integration, or otherwise writes to an external service, present a concise confirmation summary with all material details returned by the tools and supplied by the user. Include the selected creator space, exact content or item, destination/platform/account, timing, spend or audience parameters when applicable, and the requested effect.

Ask the user to confirm that exact action. A general request, an earlier approval, a draft approval, or approval for a different target does not authorize it. If a required detail is missing or changed, resolve it and present the complete action again. Never bundle materially different writes under one vague confirmation. After confirmation, call only the narrow tool for the approved action. If the tool exposes a preview or validation step, use it before committing the action.

Treat boosts and paid promotion as consequential actions. Confirm the exact post, platform, audience, budget, duration, and other available spend controls before initiating. Never infer a budget or imply that a boost ran unless BAMF returns a successful receipt.

## Media

When the user requests new media, inspect the available media-generation tools and their supported formats, controls, and costs. Gather any essential creative direction, rights constraints, and brand context before generation. Use BAMF's media tools when available; do not claim an unavailable capability or route around the connector.

Generation, upload, attachment, replacement, or deletion may create workspace or provider-side changes. Before any such write, show the precise media action and target and obtain current confirmation. Review the returned asset or generation receipt before describing the result. Do not claim an asset was saved, attached, or published without the corresponding tool receipt.

## Receipts and truthful reporting

After every approved write, inspect the tool result and report what it confirms. Include the returned item or action identifier, provider status, destination, and timestamp when available. Distinguish clearly between a proposed action, a request accepted by BAMF, a provider action confirmed by a receipt, and a result that remains pending or failed.

If a tool errors, times out, returns an ambiguous result, or omits a receipt, say that the outcome is unconfirmed. Do not retry a consequential action blindly; first check the current state for a possible duplicate, then explain the state and obtain approval again if the requested action or its details need to change.

## Connection and secrets

Use the connector's supported sign-in or reconnection flow when access is missing or expired. Never ask the user to paste an API key, OAuth token, password, or other secret into chat. Do not expose or store credentials returned by tools.
