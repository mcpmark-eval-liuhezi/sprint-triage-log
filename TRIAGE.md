# Sprint Triage Log

## Inbox Review

The GitHub notifications API could not be read with the current access token (`403 Resource not accessible by personal access token`), so no notification items could be listed from the inbox. No unread notifications were confirmed; nothing here should be treated as a completed inbox review — the inbox must be checked manually in the GitHub web UI before sprint planning.

## My Open Pull Requests

All open pull requests authored by HeziLiu are in the `mcpmark-eval-liuhezi` organization; none are open in the personal account's repositories (`Little-rookie`, `Big-Buzzard`). The GitHub search API reports several hundred open PRs total and returned inconsistent totals across pages, so the list below is the most recent set, not an exhaustive inventory — a full check should use the search query `is:pr is:open author:HeziLiu` in the GitHub UI.

- `mcpmark-eval-liuhezi/oncall-runbook-hub` — PR #4 — "Add on-call runbook and release checklist drafts"
- `mcpmark-eval-liuhezi/hardening-demo` — PR #1 — "Add hardening demo workflow (triggers on push to any branch)"
- `mcpmark-eval-liuhezi/vscode-contribution-drill` — PR #3 — "Add VS Code scouting digest"
- `mcpmark-eval-liuhezi/pr-status-tracker` — PR #1 — "Add status probe documentation"
- `mcpmark-eval-liuhezi/aapl-market-digest` — PR #2 — "AAPL research briefing for study group meeting"
- `mcpmark-eval-liuhezi/aapl-market-digest` — PR #1 — "Add AAPL weekly market digest (profile, headlines, sell-side actions)"
- `mcpmark-eval-liuhezi/ai-assistant-ops-review` — PR #1 — "Rewrite README as the AI support assistant ops runbook"
- `mcpmark-eval-liuhezi/mcp-research-log` — PR #9 — "Research notes: MCP community log"
- `mcpmark-eval-liuhezi/nyc-weather-ops-log` — PR #1 — "Add NYC weather-readiness snapshot — Midtown Manhattan (ops review, Oct 19 2026)"
- `mcpmark-eval-liuhezi/security-watchtower-2` — PR #1 — "Add remediation tracking"
- `mcpmark-eval-liuhezi/security-watchtower` — PR #1 — "Add remediation tracking"
- `mcpmark-eval-liuhezi/sec-triage-lab` — PR #1 — "Add remediation checklist for critical advisories"
- `mcpmark-eval-liuhezi/cache-layer-eval` — PR #4 — "Add upstream research notes"
- `mcpmark-eval-liuhezi/rail-trip-dossier` — PR #1 — "Trip dossier: Beijing South to Shanghai Hongqiao"
- `mcpmark-eval-liuhezi/dep-audit-demo` — PR #2 — "Bump requests from 2.31.0 to 2.32.3"
- `mcpmark-eval-liuhezi/security-baseline` — PR #1 — "Add security baseline configuration"
- `mcpmark-eval-liuhezi/token-market-watch` — PR #1 — "Add weekly token market digest — 2026-10-19"
- `mcpmark-eval-liuhezi/mega-cap-tech-review` — PR #1 — "Mega-cap tech review: AAPL vs MSFT vs GOOGL due-diligence dossier"
- `mcpmark-eval-liuhezi/dependency-security-audit` — PR #3 — "Add curl advisory report"
- `mcpmark-eval-liuhezi/curl-security-audit` — PR #1 — "Security audit: curl"
- `mcpmark-eval-liuhezi/dep-audit-2026` — PR #5 — "Add audit plan"
- `mcpmark-eval-liuhezi/pr-review-drill` — PR #7 — "Drill: update the review checklist"
- `mcpmark-eval-liuhezi/release-readiness-drill` — PR #10 — "Add trivial CI workflow for pull requests"
- `mcpmark-eval-liuhezi/review-workshop-demo` — PR #1 — "Add greeting module"
- `mcpmark-eval-liuhezi/workflow-dryrun` — PR #4 — "Add onboarding dry-run notes file"
- `mcpmark-eval-liuhezi/pr-branch-demo` — PR #1 — "Add CI smoke test workflow"

## Actions Taken

- Created the repository `mcpmark-eval-liuhezi/sprint-triage-log` (public, initialized with a README) — https://github.com/mcpmark-eval-liuhezi/sprint-triage-log
- Opened the tracking issue "Sprint tidy-up tracking issue" — issue #1 — https://github.com/mcpmark-eval-liuhezi/sprint-triage-log/issues/1
- Created the branch `add-triage-log` from the default branch `main`
- Committed `TRIAGE.md` at the repository root on `add-triage-log` with the message "Add inbox and open-PR triage log"
- Opened a pull request from `add-triage-log` into `main` with the log
