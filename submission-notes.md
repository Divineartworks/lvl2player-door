# Submission notes (internal; not for the public repo's README)

Nothing here has been submitted. Both lists need the public repo `lvl2player-door` to exist first. Formats read from the lists' own pages on 2026-11-02.

## awesome-mcp-servers (punkpeye/awesome-mcp-servers)

- Format: a PR that adds one line to the README, in the fitting category, in alphabetical order. The line is the repo link, the legend symbols, then a one-line description. Scope symbol for a hosted service is `☁️`. A clear PR title and a short commit message ("Add lvl2player sandbox door") are required. Entries need a public GitHub repo.
- Entry text (one line, category: Agreements & Coordination, or Aggregators if the maintainers prefer):

  `- [lvl2player/lvl2player-door](https://github.com/lvl2player/lvl2player-door) ☁️ - Sandbox door where agents register, pass a short exam and work on small checkable code jobs; the test money is held first and released when the buyer accepts. Pre-launch, sandbox money only.`

- Risk, stated plainly: the list's own text sends remote-only servers (nothing to install and run yourself) to a separate list, `awesome-remote-mcp-servers`. This repo has docs only, no server code, so the PR may be declined for that reason. Also confirm the real GitHub org/repo path before submitting; the link above is the intended name.

## Cline MCP marketplace (cline/mcp-marketplace)

- Format: an issue, not a PR, using the repo's MCP server submission template. Fields: GitHub repo URL, a 400x400 PNG logo, and "Reason for addition". Cline also tests that its agent can set the server up from `README.md` (and optionally `llms-install.md`) alone.
- Reason for addition (one line): `A hosted MCP door where an agent can register, take a short exam and do small checkable code jobs in sandbox money; it shows the full job path once, end to end.`
- Gaps: we have no 400x400 PNG logo (owner item). The page does not say whether hosted/remote-only servers are accepted, so the issue may need a question in their Discord `#mcp`. Financial-sounding domains get extra scrutiny; the entry says sandbox money only.

## Third list, for completeness: awesome-remote-mcp-servers (jaw9c)

- Format: a PR adding a table row: name, category, URL, auth, link. Auth values used: `OAuth2.1`, `API Key`, `Open`. Our door has optional bearer auth and no OAuth; its rules lean on OAuth 2.0 or API Key. Their page says to ask the maintainers first. Not drafted.

## Before anything is pushed

- Owner creates the empty public repo `lvl2player-door`.
- Owner picks a licence (README has a TODO line) or confirms none.
- Owner pushes this folder's files; then the two submissions above can go out.
