# Messy by Default

A hands-on workshop on real, messy data — Amsterdam housing sales from [Funda](https://www.funda.nl/), for designers, developers, and product owners at CLEVER°FRANKE.

You will load ~11,000 listings, decide what “clean” even means, look at what actually drives price, and build two honest dashboards that tell two different stories.

## What’s in this repo

| File | What it is |
|---|---|
| `Messy_by_Default_Workshop.ipynb` | The workshop notebook (empty outputs — run it yourself) |
| `Messy_by_Default_Workshop_with_outputs.ipynb` | The same notebook, already executed, so you can read charts without running anything |
| `funda.csv` | The raw dataset |

## Prerequisites

- [uv](https://docs.astral.sh/uv/) — a fast Python package manager
- That’s it. `uv` will install Python 3.11 and every library for you.

Install `uv` if you don’t have it yet:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

## Setup

From this folder:

```bash
uv sync
```

This creates a local `.venv` and installs pandas, numpy, matplotlib, seaborn, scikit-learn, and JupyterLab.

## Run the workshop

Start JupyterLab with the project environment:

```bash
uv run jupyter lab
```

Then open **`Messy_by_Default_Workshop.ipynb`** and run cells from the top with **Shift+Enter**.

If you prefer the classic notebook UI:

```bash
uv run jupyter notebook
```

### Just reading along?

Open `Messy_by_Default_Workshop_with_outputs.ipynb` instead. The charts and printed results are already there — no need to run anything.

### Using Cursor / VS Code

1. Run `uv sync` once.
2. Open either notebook.
3. Pick the kernel **`.venv`** (Python 3.11) when prompted.

## What you’ll need in the room

- About 60–90 minutes
- No coding required to take part — read the markdown, look at the charts, join the discussion
- Cells marked **Optional / Bonus** are skippable
