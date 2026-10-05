# Computational Physics Playground

Numerical projects across vector calculus, differential equations, linear
algebra, numerical methods, classical mechanics, statistical mechanics, and
astrophysics.

Each project states a physical claim, implements the governing equations, and
verifies the result numerically against theory.

**Live site:** <https://sakshamsinghsachan.github.io/computational-physics-playground/>

## Setup

```bash
python -m venv astro-env
.\astro-env\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Index

| # | Project | Claim under test |
|---|---------|------------------|
| 01 | [Vector fields and potential flow](projects/01_vector_fields_and_potential_flow/) | A field built as `F = curl(psi zhat)` is divergence free; a field with nonzero divergence admits no stream function; any periodic field splits into irrotational plus divergence free parts |

## Project structure

Each project follows the same layout:

- **Claim** -- the physical or mathematical statement being tested
- **Equations** -- the governing relations, written out
- **Method** -- numerical algorithm used
- **Results** -- figures and measured quantities
- **Verification** -- error metrics compared against theoretical prediction
- **Conclusion** -- whether the claim holds, and to what accuracy

Notebooks are committed with outputs executed, so every number quoted in a
README can be traced to the code that produced it.

## Planned projects

02 ODE phase portraits &middot; 03 rank-1 SVD blackbody extraction &middot;
04 numerical convergence suite &middot; 05 residue theorem integrals &middot;
06 Poisson solver by finite differences &middot; 07 two-body orbits &middot;
08 hydrogen by finite differences &middot; 09 Ising Metropolis &middot;
10 blackbody explorer &middot; 11 Lane-Emden polytropes &middot;
12 exoplanet radial velocity detection

## Notes

- `notes/equation_cards/` -- one card per equation: statement, symbols and
  units, short derivation, physical meaning, example problem
- `notes/derivations/` -- longer derivations worked out in full
- `docs/` -- GitHub Pages source, built from the notebooks
