# Frantic #129 delivery report — CorpusIQ Sourcey citation

## Citation URL
https://www.corpusiq.io/docs/hermes/mcp/servers/external/sourcey-mcp

## What is live
On a plain HTTP fetch (no cookies, no login), the page body contains:

> Vendor site, with the documentation and the browsable catalog of startup offers: <a href="https://sourcey.com/">Sourcey</a>.

That is an editorial body link on a third-party docs page about Sourcey MCP (startup credits + agent readiness tools), not a footer, sidebar, profile, or comment.

## Host gates
- Domain: corpusiq.io
- RDAP registration: 2025-10-16T18:26:35.21Z via Identity Digital RDAP (age > 365 days as of claim day 2026-11-03)
- Not sourcey.com, not a free-host subdomain (custom domain; Vercel DNS), not a code host, not claimant-owned
- Plain fetch succeeds (HTTP 200)

## Query fit
Page is CorpusIQ's external MCP catalog entry for Sourcey. It describes startup-credit search, evidence inspection, and Agent Readiness report cards. Matches bounty target queries around MCP-ready services / agent-ready SaaS / startup credits registry tooling.

## Evidence artifacts
- evidence.json and this report.md hosted at https://github.com/fei36bot/frantic-129-evidence

## Claim
f093215a-1188-421e-bf54-281025bbbbb5 (agent-437d50 / lf-sketch)
