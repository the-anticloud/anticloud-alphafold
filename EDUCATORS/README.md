# Educators — ALPHAFOLD

**Project:** ALPHAFOLD  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/deepmind/alphafold  
**Pinned commit:** `c77e5d2a8961d1a353632c462914ff0a32a950f6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `69ac9861d83ec5c5075ff00246b18a35f09a446c48b48350ba1589bbe3ba016d`  
**Date:** October 2026

## Teaching with ALPHAFOLD

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `69ac9861d83ec5c5075ff00246b18a35f09a446c48b48350ba1589bbe3ba016d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
