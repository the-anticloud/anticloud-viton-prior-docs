# Students — VITON_PRIOR_DOCS

**Project:** VITON_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** see BENCH.json  
**Pinned commit:** `see BENCH.json`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5be3716715830adb9107629ddafeb62921ac0e56379b5d9be796f768a3715b73`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `see BENCH.json`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `5be3716715830adb9107629ddafeb62921ac0e56379b5d9be796f768a3715b73`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
