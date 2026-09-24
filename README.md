# King’s Seal QR Trust Demo

**Patent Pending**

Live interactive prototype of the **King’s Seal** system.

**JavaScript Version** (instant, works on iPad/mobile):
https://unnombrechido.github.io/kings-seal-demo/demo.html

**Site:** https://kingssealqr.com

**Python Notebook Version** (advanced):
https://jupyterlite.github.io/demo/repl/index.html?repo=https://github.com/unnombrechido/kings-seal-demo&path=demo.ipynb

The browser demo now matches the Python disclosure:
- Tag = first 16 hex chars of `HMAC-SHA256(issuer_secret, payload)`
- Format = `seal:{issuer_id}|tag:{tag}|{payload}`
- Issuer registry mirrors `unnombrechido/kings-seal` `registry.json`

Generate sealed QRs, verify pasted seals, test shortened URL enforcement.

**Original Idea & Disclosure:**
https://github.com/unnombrechido/kings-seal

King’s Seal™ by Omar David Puente Trejo — December 2025
