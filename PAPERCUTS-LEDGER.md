# Papercuts

## 2026-07-25T16:41:47Z · unknown · joshuaizzard · agentsview:. · 019f9a22-ccdb-7570-9bcc-c6ccf045511d

Running focused Go sync tests → checkout lacked internal/pricing/snapshot/litellm_snapshot.json.gz required by go:embed, so tests fail during setup before compiling; the test prerequisite is not surfaced by the focused-test command.

## 2026-07-25T17:33:58Z · unknown · joshuaizzard · agentsview:frontend · 019f9a54-8205-7610-8255-bf1f64c63964

Reverting generate:api drift with apply_patch → terminal blank lines in generated TypeScript files were not restored exactly, so a targeted git restore was needed for files created solely by this verification run.

## 2026-07-25T17:35:20Z · gpt-5.6-sol · joshuaizzard · agentsview:. · 019f9a17-80a1-7de3-869a-9e2fd08c80f7

Verifying the npm security fix with npm run generate:api before npm run check → regenerated client code is incompatible with existing call sites (required request arguments appeared), so the check fails until generated-only drift is reverted; the documented verification sequence does not surface that the committed client is intentionally or accidentally stale.
