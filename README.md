# IZLO — Optimization Model in SMT-LIB

One self-contained SMT-LIB model (`projekt2.smt2`):

- `x = 2·A·B` over integers with piecewise-linear y / z
- Minimize `D + E > 0` subject to `z < E + D`
- A negated-exists assertion proving minimality
- Five test vectors inlined via `check-sat-assuming`

## Run

```bash
z3 projekt2.smt2        # or any SMT-LIBv2 solver
```

Coursework for *Logika a grafové algoritmy (IZLO)* at FIT VUT Brno.
