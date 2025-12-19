# King's Seal QR Trust Prototype
20205/12/19
**A simple, secure way to make QR codes trustworthy — especially those with shortened URLs.**

This prototype demonstrates the "King's Seal" concept:
- Verified issuers add a lightweight HMAC-based seal.
- Scanners verify the seal and show trust level.
- Shortened URLs require a seal to be trusted.

**Live Demo** → Click here: [Open Interactive Demo](./notebooks/demo.ipynb)

(Uses JupyterLite — runs entirely in your browser, no install needed)

**How it works**
- Choose an issuer
- Enter a payload (URL or text)
- Generate → see sealed QR + verification status

The seal prevents tampering and enforces trust for risky shortened links.

**Originated by unnombrechido — December 18, 2025**

Public domain / open source — feel free to fork, improve, or build on it.

---
See the [original idea disclosure](https://github.com/unnombrechido/Kings_seal) for full background.
