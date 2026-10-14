# Ethics — PVGIS

**Project:** PVGIS  
**Category:** SOLAR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7afa341603d5d2adecdfd3cddceed64bd1f69d46`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b9beffa1910376c70b9371276e910ba8d49c88b2a2e5fa5e7b666f3ca50a4a9f`  
**Date:** October 2026

## Position

PVGIS is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
