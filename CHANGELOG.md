# Changelog

## 1.1.0 — 2026-06-12
- Added event-level logging (events.csv)
- Added global experiment clock for precise timestamping
- Added log_event() utility for standardized event recording
- Added timestamped logging of:
  - task_start
  - task_end
  - pump
  - cashout
  - explosion
- Improved compatibility with EEG and other physiological recording workflows
- Added automatic data directory creation
- Improved project organization and asset management
- Behavioral outputs remain unchanged:
  - subjects.csv
  - trials.csv
  - blocks.csv
- Added new output:
  - events.csv

## 1.0.0 — 2025-12-22
- Initial public release
- Single-page intro (centered, concise)
- Practice (3) and main (60) trials
- Dark-grey prompt boxes for bottom commands
- Balloon growth clamped to left panel; no outline; visible growth per press
- Deterministic explosion threshold; counterfactual potential
- Block summaries at 20/40 and final summary at 60
- CSV outputs: subjects, trials, blocks
