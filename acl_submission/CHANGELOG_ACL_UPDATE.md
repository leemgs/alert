# ACL submission update (2026-10-06)

## Statistical honesty (regenerated experiment outputs)
- Table 3: marginal 95% bootstrap half-widths (~±0.09–0.10 on n=82); paired ALERT–B5 ΔF1 +0.04, 95% CI [−0.09, +0.18] (includes zero).
- RQ1 text no longer claims p<0.05 vs B5; gap described as modest/directional.
- PLRE full-vs-flat: paired ΔF1 CI [0.03, 0.10], p<0.001.
- Distractor-free subset reported: ΔF1 +0.03, 95% CI [−0.01, +0.07].
- Abstract and Limitations aligned with the above.
- Calibration 150 cases stated as disjoint from the 82 human test cases (already in setup).

## Bundle
- `experiment_outputs/*.csv` — regenerated CSVs (schema = analysis/templates); replace with recovered server logs if available.
- `experiment_outputs/stats_out/review_stats.md` — compute_review_stats.py log.

## Build note
- Full `pdflatex` may need `algorithm`/`algorithmic` packages on the build host.
