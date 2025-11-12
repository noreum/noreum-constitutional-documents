[![Signature Verification](https://github.com/noreum/noreum-constitutional-documents/actions/workflows/verify-signatures.yml/badge.svg)](https://github.com/noreum/noreum-constitutional-documents/actions/workflows/verify-signatures.yml)
[![Verified by Noreum Cold Key](https://img.shields.io/badge/Verified%20by-Noreum%20Cold%20Key-gold?style=flat-square)](https://github.com/noreum/noreum-constitutional-documents)

#  Noreum Constitutional Documents

**Official Public Repository for Noreum Foundational and Constitutional Documents**

This repository contains the **foundational preamble, whitepaper, and manifest signatures** of the Noreum Network.  
All documents are **cryptographically signed** using the *Noreum Cold Signing Key* to preserve authorship and historical authenticity.

---

###  Contents

| File | Description |
|------|--------------|
| `Preamble to the Noreum Constitution.pdf` | Foundational whitepaper (official document) |
| `Preamble to the Noreum Constitution.pdf.asc` | GPG detached signature |
| `manifest_preamble_v1.txt` | Manifest entry linking the document to chainId 1177 |
| `manifest_preamble_v1.txt.asc` | GPG signature of the manifest |

---

###  Verification

To verify both signatures locally:
A message saying
Good signature from "Noreum Cold Signing Key <sign@noreum.org>"
confirms the authenticity and integrity of the publication.
© 2025 Noreum Foundation — Released under Creative Commons CC BY 4.0
gpg --verify "Preamble to the Noreum Constitution.pdf.asc" "Preamble to the Noreum Constitution.pdf"
gpg --verify "manifest_preamble_v1.txt.asc" "manifest_preamble_v1.txt"
