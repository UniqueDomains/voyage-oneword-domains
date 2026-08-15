# Available .VOYAGE One-Word Domains (16,104)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C104%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .voyage one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,104 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,104 domains · **Median ask:** $11.36 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-15
**Canonical page:** `https://unique.domains/domains/tld/voyage`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/voyage?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./voyage.csv">CSV</a> / <a href="./voyage.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VOYAGE search](https://unique.domains/domains/tld/voyage?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VOYAGE search](https://unique.domains/domains/tld/voyage?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VOYAGE one-word domain catalog.

### Files

- `voyage.csv`, public CSV extract (1,000 rows)
- `voyage.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/voyage-oneword-domains/main/voyage.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| apt.voyage     | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| hub.voyage     | resell    | —         | —             | high           | medium | 3      | Dynadot Inc                                               |
| net.voyage     | premium   | $500      | —             | high           | medium | 3      | name.com                                                  |
| bow.voyage     | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| deep.voyage    | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC - 20                                         |
| NYC.voyage     | premium   | $78.54    | $78.54        | high           | medium | 3      | namesilo                                                  |
| boy.voyage     | available | $9.99     | —             | medium         | low    | 3      | name.com                                                  |
| game.voyage    | resell    | —         | —             | high           | medium | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| asia.voyage    | premium   | $500      | —             | high           | low    | 4      | name.com                                                  |
| clv.voyage     | available | $9.99     | $83.99        | low            | low    | 3      | name.com                                                  |
| virtual.voyage | resell    | —         | —             | medium         | medium | 7      | Spaceship, Inc.                                           |
| sell.voyage    | premium   | $118.80   | $118.80       | high           | medium | 4      | namesilo                                                  |
| clx.voyage     | available | $9.99     | $83.99        | low            | low    | 3      | name.com                                                  |
| ticket.voyage  | premium   | $118.80   | $118.80       | high           | low    | 6      | namesilo                                                  |
| dig.voyage     | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| gourmet.voyage | premium   | $123.75   | —             | high           | low    | 7      | name.com                                                  |
| DJI.voyage     | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| premier.voyage | premium   | $118.80   | $118.80       | high           | low    | 7      | namesilo                                                  |
| due.voyage     | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| premium.voyage | premium   | $118.80   | $118.80       | high           | low    | 7      | namesilo                                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,104 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/voyage?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/voyage?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

Each name in this .voyage set pairs a short, ownable word with a niche extension often tied to travel, motion, and adventure branding. With a median ask near $12, most listings sit close to standard registration pricing, which makes side-by-side comparison straightforward. When comparing these domains, weigh word clarity, spelling simplicity, and thematic fit against the asking price and renewal cost before choosing one.

- 12,563 one-word .voyage domains in this set
- Median ask near $12 — standard registration range
- Mix of playful, descriptive, and action-based names
- Compare brandability, spelling ease, and renewal cost

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VOYAGE One-Word Domains*. Version 2026-08-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VOYAGE page](https://unique.domains/domains/tld/voyage?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_voyage_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
