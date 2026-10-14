# Students — PVGIS

**Project:** PVGIS  
**Category:** SOLAR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7afa341603d5d2adecdfd3cddceed64bd1f69d46`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b9beffa1910376c70b9371276e910ba8d49c88b2a2e5fa5e7b666f3ca50a4a9f`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `7afa341603d5d2adecdfd3cddceed64bd1f69d46`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b9beffa1910376c70b9371276e910ba8d49c88b2a2e5fa5e7b666f3ca50a4a9f`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
