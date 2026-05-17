# harnexa-express

A scratchpad for experiments and notes built on top of [`nexa-gauge`](https://pypi.org/project/nexa-gauge/).

This is **not** a library or shippable software — just a place to keep small scripts, one-off experiments, and the notes that go with them.

## Layout

```
.
├── src/         # experiment scripts
├── results/     # run outputs (gitignored)
└── *.story.md   # per-experiment write-ups (gitignored)
```

## Setup

Requires Python 3.10+.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .
```

This installs `nexa-gauge` with the `huggingface` extra.

## Conventions

- One script per experiment under `src/`.
- Outputs go to `results/` — never committed.
- Each experiment may have a sibling `*.story.md` capturing what was tried, what happened, and what to do next. These are local-only.
