# Computational Physics Playground

Numerical projects across vector calculus, differential equations, linear
algebra, numerical methods, classical mechanics, statistical mechanics, and
astrophysics.

Each project states a physical claim, implements the governing equations, and
verifies the result numerically against theory.

## Setup

```bash
python -m venv astro-env
.\astro-env\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Index

| # | Project | Claim under test |
|---|---------|------------------|
| 01 | Vector fields and potential flow | Helmholtz decomposition: `∇·F = 0` and `curl F = 0` imply `F = ∇ψ` |

## Project structure

Each project follows the same layout:

- **Claim** — the physical or mathematical statement being tested
- **Equations** — the governing relations, written out
- **Method** — numerical algorithm used
- **Results** — figures and measured quantities
- **Verification** — error metrics compared against theoretical prediction
- **Conclusion** — whether the claim holds, and to what accuracy

## Notes

- `notes/equation_cards/` — one card per equation: statement, symbols and
  units, short derivation, physical meaning, example problem
- `notes/derivations/` — longer derivations worked out in full
