# Students — MAILPILE

**Project:** MAILPILE  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** https://github.com/mailpile/Mailpile  
**Pinned commit:** `741e610f3e765f03bd0c452c92c6758280e7f99f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c2a153c2adbd13a308fa0d41d98dfcf702243997caea25b3e9d30b0cb32fe056`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `741e610f3e765f03bd0c452c92c6758280e7f99f`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `c2a153c2adbd13a308fa0d41d98dfcf702243997caea25b3e9d30b0cb32fe056`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
