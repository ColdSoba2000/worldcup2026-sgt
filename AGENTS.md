# AGENTS.md — agent entry point

This repo has no CLAUDE.md project contract yet — read the README and recent git log for orientation.

The estate-wide operating manual — workflow gates, orchestration roles, automation
inventory, SecondBrain vault navigation, and the break-glass takeover prompt — lives in
the private estate repo: **github.com/ColdSoba2000/claude-setup** (start at RUNBOOK.md).

House rules that bind ANY agent in this repo:

1. **Nothing merges to main without a current review record** — `reviews/<branch>-<SHA>.md`
   (gitignored, machine-local). No record for the exact HEAD SHA = run a review first.
   Fail closed.
2. **Sessions end with a handover** committed to `docs/handovers/` (dated filename;
   newest dated file is the truth — there is no latest.md).
3. **Workflow changes that affect more than one project** need a decision page in the
   SecondBrain vault (`wiki/products/claude-workflow/decisions/`) before they land.
