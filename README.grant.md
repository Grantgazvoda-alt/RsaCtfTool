# RsaCtfTool — Forked for Grant's Toolkit

**Original:** RsaCtfTool — https://github.com/Ganapati/RsaCtfTool
**Forked:** 2026-11-03
**Language:** Python

## What it is

RSA attack tool for CTFs. Recovers private keys from weak public keys and uncipers data using Wiener, Boneh-Durfee, Franklin-Reiter, and other cryptanalytic methods.

## Why it's here

Crypto challenge solver and a reference for understanding RSA weakness patterns during authorized crypto assessments.

## Quick start

```bash
python3 RsaCtfTool.py --publickey key.pub --uncipherfile flag.enc
```

## Related forks

- pwntools — general exploit dev
- php2shell PoC — PHP memory-safety research

## Scope note

CTF labs and authorized crypto research only.
