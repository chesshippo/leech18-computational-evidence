# Order-18 Leech-Tree Computational Evidence

This is the computational evidence for the computer-assisted proof that no Leech tree of order 18 exists.

The complete evidence is the `v1.0.0` release asset named `leech18_computational_evidence_v1.0.0.tar.gz`.

- Size: 24,204,350 bytes
- SHA-256: `3b53ced3f8d0b8aff0798d446fdb6256e3ad688429df090a7f915849b59d23b8`

After extraction, run the full verification from the extracted artifact root with:

```sh
python3 verification/verify_release.py verify-release --root .
```

Expected output:

```text
CLEAN_RELEASE_VERIFY_OK records=39672 configurations=8
```

Code is licensed under Apache-2.0 (see `LICENSE`), and evidence data is licensed under CC-BY-4.0 (see `LICENSE-DATA`).
