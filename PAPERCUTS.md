# Papercuts live queue

<!-- papercuts-generated-view: {"kind":"active","ledger":"PAPERCUTS-LEDGER.md","manifest":"PAPERCUTS-TRIAGE.json","ledgerSha256":"2374eb538913cadc3b53c60e7ba16064c26680d5a5860d9380b2eb01dfc4b7b7","manifestSha256":"1a457248b6ea538f49f8e05de914fe554eb97eec0c6676124d44562e0ce5b6c8","sourceEntryCount":3,"newestSourceTimestamp":"2026-07-25T17:35:20Z"} -->
> **Generated — do not edit.** Run `papercuts refresh`; raw history remains in `PAPERCUTS-LEDGER.md`.

## Open groups

| ID | Status | Count / date range | Task | Issue | Owner |
|---|---|---|---|---|---|
| — | — | — | No open groups | — | — |

## Untriaged ledger entries

| Entry | Timestamp | Message |
|---:|---|---|
| 1 | 2026-07-25T16:41:47Z | Running focused Go sync tests → checkout lacked internal/pricing/snapshot/litellm_snapshot.json.gz required by go:embed, so tests fail during setup before compiling; the test prerequisite is not surfaced by the focused-test command. |
| 2 | 2026-07-25T17:33:58Z | Reverting generate:api drift with apply_patch → terminal blank lines in generated TypeScript files were not restored exactly, so a targeted git restore was needed for files created solely by this verification run. |
| 3 | 2026-07-25T17:35:20Z | Verifying the npm security fix with npm run generate:api before npm run check → regenerated client code is incompatible with existing call sites (required request arguments appeared), so the check fails until generated-only drift is reverted; the documented verification sequence does not surface that the committed client is intentionally or accidentally stale. |
