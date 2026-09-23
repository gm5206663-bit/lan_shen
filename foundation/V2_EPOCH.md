# V2 EPOCH — 2026-09-23

**Author-ordered full rebuild.** V1 (15 chapters, verify 72,577 / style 72,473) retired to
`_archive/v1_epoch_ch01-15/` — archived, not deleted, per the author's own convention.
V1's banked LAWS carry; its scene FACTS do not bind (REBUILD_PLAN.md: contradictions must
be named in boards). V2: Fire Phoenix register, §0.7 ceilings at draft time, ~2 canon
chapters per serial chapter, Book One ends at the academy-entrance arc close (end beat
locked when canon 095–105 receipts land). Map: foundation/REBUILD_PLAN.md.

| ch | canon | title | banked |
|---|---|---|---|
| 1 | 001–002 | What the Master Said | 3,758w style / 3,793 verify / dual-track canon-parallel / 9 gates green |

## GIT WORKFLOW (repo management law, 2026-09-23)

- **Main is the shipping branch.** One commit per chapter: message = `chN: Title
  (canon XXX–YYY) — gates green` plus any doctrine notes.
- **Tag chapters**: `v2-chNN` after each chapter's battery goes green (`v2-ch01` exists).
- **Docs ride with the chapter** (SERIAL_LOG, CANON_LEDGER, STATUS_PANEL, totals) in the
  same commit — the repo is never left in a state where docs disagree with chapters.
- **House files are permanent**: LICENSE (MIT © Gaurav Meena) + NOTICE.md (Soul Land IP
  disclaimer) — pattern matched to soul-library.
- **No tokens in the tree, ever.** Remote URL carries none; pushes use the token on the
  command line only. Battery layer 5 greps for leaks each chapter.
