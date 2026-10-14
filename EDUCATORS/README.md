# Educators — MAILPILE

**Project:** MAILPILE  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** https://github.com/mailpile/Mailpile  
**Pinned commit:** `741e610f3e765f03bd0c452c92c6758280e7f99f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c2a153c2adbd13a308fa0d41d98dfcf702243997caea25b3e9d30b0cb32fe056`  
**Date:** October 2026

## Teaching with MAILPILE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `c2a153c2adbd13a308fa0d41d98dfcf702243997caea25b3e9d30b0cb32fe056` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
