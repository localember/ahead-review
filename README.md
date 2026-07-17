# AHEAD homepage — client review preview

Live: **https://localember.github.io/ahead-review/** (noindex)

A static snapshot of the AHEAD HR homepage for async client review — no server to keep running.
Frozen from the local Breakdance build (post 235) on 2026-07-17. Includes the cost-calculator form
and John's copy edits.

**The form renders but does not submit** (no backend on a static page) — a submit shows a "design
preview" note. On the live site it posts to AHEAD's GoHighLevel webhook.

To update after a build change: re-freeze from the sandbox, copy the files here, then
`git add -A && git commit -m "update preview" && git push` (Pages redeploys the same URL in ~1 min).
