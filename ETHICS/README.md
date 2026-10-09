# Ethics — ALPHAFOLD

**Project:** ALPHAFOLD  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/deepmind/alphafold  
**Pinned commit:** `c77e5d2a8961d1a353632c462914ff0a32a950f6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `69ac9861d83ec5c5075ff00246b18a35f09a446c48b48350ba1589bbe3ba016d`  
**Date:** October 2026

## Position

ALPHAFOLD is packaged for offline deployment with a verifiable audit trail. The
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
