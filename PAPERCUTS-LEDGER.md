# Papercuts

## 2026-07-25T16:41:47Z · unknown · joshuaizzard · agentsview:. · 019f9a22-ccdb-7570-9bcc-c6ccf045511d

Running focused Go sync tests → checkout lacked internal/pricing/snapshot/litellm_snapshot.json.gz required by go:embed, so tests fail during setup before compiling; the test prerequisite is not surfaced by the focused-test command.
