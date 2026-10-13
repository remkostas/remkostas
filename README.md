### Remko Stas

I work on supply chain processes at Accenture in Hamburg, mostly inside aerospace warehouse operations.

On the side I build the tools I wish operations had. Then I measure whether they actually hold up.

**What's here**

- **[n8n-wms](https://github.com/remkostas/n8n-wms)**: a barcode warehouse terminal on n8n and PostgreSQL. Receiving, picking and stock lookup for handheld scanners. Ten operators receiving the same article at once still leave stock and ledger in exact agreement. The README explains why I decided not to sell it.
- **[Controlled-Copy](https://github.com/remkostas/Controlled-Copy)**: a NotebookLM-style notebook for controlled documents. Every statement links to the passage it came from, every quote is checked against its source, and outdated revisions never back an answer.
- **[card2vcard](https://github.com/remkostas/card2vcard)**: photo of a business card in, ready-to-import .vcf and QR code out.
- **[PII-Redactor](https://github.com/remkostas/PII-Redactor)**: finds and redacts IBANs, emails, phone and card numbers in the browser. Nothing gets uploaded.
- **[boarding-pass-scanner](https://github.com/remkostas/boarding-pass-scanner)**: reads PDF417 and Aztec boarding pass barcodes from a photo, fully offline.

**How I build**

- Plain tools first. One Postgres database and a Compose file go a long way.
- Measure before claiming. Tests and benchmarks live next to the code.
- Private by default. The small tools run locally in your browser.

Outside these repos: 200+ n8n workflows on a self-hosted server at home, orchestrating several AI models.

**Stack:** n8n · Python · JavaScript · PostgreSQL · Docker · LLMs and agentic AI · Celonis

[LinkedIn](https://www.linkedin.com/in/remkostas) · [remkostas.com](https://remkostas.com)
