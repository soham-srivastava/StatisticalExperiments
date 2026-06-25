# StatisticalExperiments

A running collection of small, self-contained statistics and quant experiments. Each one lives in its own file or folder, answers one specific question, and is meant to be read top-to-bottom without needing the rest of the repo.

## Structure

No fixed layout — each experiment is added as either a single notebook/script or its own subfolder, named for what it tests. Plots, data, and write-ups for an experiment stay next to its code.

## Conventions

- Each experiment states the question it's answering up front, not just the method.
- Where there's a "which is better" question, answer it with a measurable test (e.g. coverage, error, backtest result) — not just a visual.

## Current experiments

- `bollinger_normal_vs_t_1.ipynb` — fixed-multiplier vs. Student-t-multiplier Bollinger Bands, compared by empirical coverage on candlestick price data.

(more added as they're run)
