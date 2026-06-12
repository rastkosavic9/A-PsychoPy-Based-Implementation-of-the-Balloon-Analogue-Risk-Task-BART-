# Balloon-Analogue-RIsk-Task-PsychoPy-Implementation
A PsychoPy (Python) implementation of the Balloon Analogue Risk Task (BART; Lejuez et al., 2002), adapted with multiple balloon types and explicit risk parameters. Designed for behavioral research and EEG-compatible event logging.
**Citation / DOI:** Savic R. (2026). * Balloon Analogue Risk Task (BART) in PsychoPy* [Computer software]. Zenodo. [https://doi.org/10.5281/zenodo.18121801](https://doi.org/10.5281/zenodo.18121801)


## Features
- Single-page intro (centered, concise; black text on light-grey background)
- Practice (3) and main (60) trials
- Left-side balloon (no outline); gradual growth per pump (visible +1 px minimum), clamped to a panel
- Right-side HUD on dark-grey cards (white text)
- Bottom command prompts on dark-grey boxes (white text) for visibility
- Deterministic explosion threshold per trial (reproducible; correct counterfactual potential)
- Block summaries after 20 and 40 trials; final summary after 60 trials


## Outputs

The task generates four CSV files:

- subjects.csv — participant demographics and session information
- trials.csv — trial-level behavioral data
- blocks.csv — block-level summary statistics
- events.csv — timestamped event log (pump, cashout, explosion, task_start, task_end)

The events.csv file can be used for synchronization with physiological recordings such as EEG.


## Reference

Lejuez, C. W., Read, J. P., Kahler, C. W., Richards, J. B.,
Ramsey, S. E., Stuart, G. L., Strong, D. R., & Brown, R. A.
(2002). Evaluation of a behavioral measure of risk taking:
The Balloon Analogue Risk Task (BART).
Journal of Experimental Psychology: Applied, 8(2), 75–84.


## Requirements

**Option A (recommended): PsychoPy Standalone (2024+)**

**Option B (Python environment):**
```bash
pip install -r requirements.txt
