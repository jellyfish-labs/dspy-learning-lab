# DSPy Learning Lab

A practical guide to building and improving language-model applications with DSPy.

## Highlights

- Step-by-step DSPy examples
- Evaluation and optimization workflows
- Supporting infrastructure examples

## Quick start

Python 3.9 or newer is required.

```bash
python -m venv .venv
```

Activate the virtual environment before installing dependencies.

**macOS/Linux:**

```bash
source .venv/bin/activate
```

**Windows (PowerShell):**

```powershell
.venv\Scripts\Activate.ps1
```

```bash
python -m pip install -e .
```

Copy `.env.example` to `.env`, add the provider credentials you plan to use, and begin with the examples under `examples/basic`.

## Learning path

1. Read `docs/01_motivation.md` for the problems DSPy is designed to solve.
2. Continue with `docs/02_core_concepts.md` to learn the main abstractions.
3. Run the small programs in `examples/basic`.
4. Explore `examples/advanced` for optimization and validation patterns.
5. Use `examples/infrastructure` and `examples/personas` for larger application patterns.

## Project checks

```bash
pytest
dspy-evaluate
```

The test suite validates the guide code, while the installed evaluation command runs the project's evaluation workflow.

## Source

Based on [evalops/dspy-0to1-guide](https://github.com/evalops/dspy-0to1-guide). Review the upstream documentation and licensing terms before redistribution or production use.
