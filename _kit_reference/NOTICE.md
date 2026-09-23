# `_kit_reference/` is VENDORED, NOT LIVE

This directory is a byte-identical copy of `SOUL_LAND_UNIVERSAL_KIT` from
`github.com/gm5206663-bit/soul-land-universal-kit`, vendored here so that this repository is
self-contained for a reader who clones it and has no other checkout.

🔴 **NOTHING IN THIS DIRECTORY IS AUTHORITATIVE FOR THIS SERIAL.**

| This directory | The live file | Relationship |
|---|---|---|
| `_kit_reference/tools/verify.py` | `tools/verify.py` | **a fork.** Upstream **v2.2** verbatim plus two local gates (8 panel field discipline, 9 en-dash year range) |
| `_kit_reference/tools/selftest.py` | `tools/selftest.py` | **a fork.** 409 lines differ — this serial injects its own defect set |
| `_kit_reference/00…10_*.md` | `foundation/NO_MISTAKE_LIVE_RULES.md`, `foundation/STYLE_LAW.md` | the kit's law documents, **read as source**, restated here only where this serial tightens them |
| `_kit_reference/templates/*.md` | `foundation/*.md`, `codex/*.md` | the shapes this serial's files were built from |

**Why the copy is kept even though the TWO-COPIES LAW normally forbids it.** That law is about
*facts*: "a fact maintained in two places will be wrong in one of them, and the check reads the
other." A vendored dependency is not a fact, it is a pinned version — provided it is labelled as
pinned and never edited. **It has never been edited, and it must not be.** If the upstream kit
changes, re-vendor the whole directory in one commit; do not patch a file inside it.

🔴 **RE-VENDORED 2026-09-20 to upstream v2.2** (kit commit `ee9969d1`, *"SL2 The Unraveled
Tide: Size-2 re-rail + unified verify gate (v2.2)"*). Only `tools/verify.py` and
`tools/selftest.py` changed upstream in that commit; the law documents and templates did not,
so they are untouched and still current. The previous vendored copy was v1 (288 lines); v2.2 is
598. `tools/verify.py` was rebased onto v2.2 in the same pass, carrying the two local gates
forward. Layer 8 now runs v2.2's own 22-check selftest, including the red-tests that name-digits
(`Room 108`, `Dorm333`) pass while measurement digits (`rank 29`) still fail.

**The one exception, and it is a live gate:** `_kit_reference/tools/selftest.py` is executed by
layer 8 of `checks/run_all.sh`. It proves that this serial's forked `verify.py` has not broken
any gate it inherited from the kit. That is a deliberate use of the vendored copy as a
regression baseline, which is the only reason a stale copy is safe to keep.

The underscore prefix marks the directory as non-live. It sorts first so that a reader opening
the repository sees this notice before anything else.
