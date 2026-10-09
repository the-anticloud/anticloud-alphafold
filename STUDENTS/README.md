# Students — ALPHAFOLD

**Project:** ALPHAFOLD  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/deepmind/alphafold  
**Pinned commit:** `c77e5d2a8961d1a353632c462914ff0a32a950f6`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `69ac9861d83ec5c5075ff00246b18a35f09a446c48b48350ba1589bbe3ba016d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `c77e5d2a8961d1a353632c462914ff0a32a950f6`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `69ac9861d83ec5c5075ff00246b18a35f09a446c48b48350ba1589bbe3ba016d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
