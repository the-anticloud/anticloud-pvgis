# Educators — PVGIS

**Project:** PVGIS  
**Category:** SOLAR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7afa341603d5d2adecdfd3cddceed64bd1f69d46`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b9beffa1910376c70b9371276e910ba8d49c88b2a2e5fa5e7b666f3ca50a4a9f`  
**Date:** October 2026

## Teaching with PVGIS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `b9beffa1910376c70b9371276e910ba8d49c88b2a2e5fa5e7b666f3ca50a4a9f` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
