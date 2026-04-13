# Arts One-Word Domains (0)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-0%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of arts one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 10,000 rows · **Live catalog:** 0 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/sector/arts`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/sector/arts?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./arts.csv">CSV</a> / <a href="./arts.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this exact search](https://unique.domains/domains/sector/arts?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this exact search](https://unique.domains/domains/sector/arts?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for the exact Unique Domains search represented by `https://unique.domains/domains/sector/arts`.

### Files

- `arts.csv` — public CSV extract (10,000 rows)
- `arts.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/arts-oneword-domains/main/arts.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price   | renewal_price | attractiveness | demand | length | registrar                  |
| ---------------- | --------- | ----------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| visualart.zone   | available | $51.98      | —             | 64             | 92     | 10     | namecheap                  |
| studies.org      | resell    | $101,200    | $21.99        | —              | 84     | 7      | GoDaddy.com, LLC           |
| visualart.dev    | premium   | $61.25      | $61.25        | 64             | 92     | 10     | name.com                   |
| visualart.tech   | available | $13.99      | $84.99        | 64             | 92     | 10     | name.com                   |
| aesthetics.me    | resell    | $5,748.85   | $26.99        | 62             | 80     | 10     | Dynadot Inc                |
| visualart.app    | premium   | $4,370      | $26.99        | 64             | 92     | 10     | name.com                   |
| visualart.ninja  | available | $42.98      | —             | 64             | 92     | 10     | namecheap                  |
| ceramics.xyz     | resell    | $114,871.20 | $20.99        | 58             | 80     | 8      | Dynadot LLC                |
| theater.zone     | premium   | $128.70     | $128.70       | 72             | 88     | 7      | namecheap                  |
| visualart.gg     | available | $82.98      | —             | 64             | 92     | 10     | namecheap                  |
| ceramics.co      | resell    | $6,323.85   | $48.99        | 58             | 80     | 8      | Spaceship, Inc.            |
| theater.tech     | premium   | $781.25     | $3,125        | 72             | 88     | 7      | name.com                   |
| visualart.expert | available | $82.48      | —             | 64             | 92     | 10     | namecheap                  |
| sculpture.me     | resell    | $791.20     | $27.99        | 84             | 72     | 9      | GoDaddy.com, LLC           |
| theater.store    | premium   | $312.50     | $1,250        | 72             | 88     | 7      | name.com                   |
| visualart.cloud  | available | $32.98      | —             | 64             | 92     | 10     | namecheap                  |
| creative.red     | resell    | $5,290      | $29.99        | 92             | 45     | 8      | Squarespace Domains II LLC |
| theater.space    | premium   | $812.50     | $3,250        | 72             | 88     | 7      | namecheap                  |
| theater.ninja    | available | $42.98      | —             | 72             | 88     | 7      | namecheap                  |
| creative.blue    | resell    | $9,775      | $35.99        | 92             | 45     | 8      | Squarespace Domains II LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 0 live domains                                   |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/sector/arts?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/sector/arts?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Arts One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live search](https://unique.domains/domains/sector/arts?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_arts_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
