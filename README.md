# Available .LONDON One-Word Domains (31,840)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-31%2C840%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .london one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **31,840 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 31,840 domains · **Median ask:** $70.46 · **High-demand under $2,500:** 36

**Last updated:** 2026-09-25
**Canonical page:** `https://unique.domains/domains/tld/london`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/london?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./london.csv">CSV</a> / <a href="./london.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LONDON search](https://unique.domains/domains/tld/london?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LONDON search](https://unique.domains/domains/tld/london?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LONDON one-word domain catalog.

### Files

- `london.csv`, public CSV extract (1,000 rows)
- `london.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/london-oneword-domains/main/london.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------------------- |
| arty.london     | available | $12.98    | $41.98        | high           | low    | 4      | namecheap                                |
| table.london    | resell    | —         | —             | high           | low    | 5      | Porkbun, LLC                             |
| and.london      | premium   | $681.70   | —             | high           | medium | 3      | name.com                                 |
| atop.london     | available | $31.99    | $31.99        | high           | low    | 4      | namesilo                                 |
| dentist.london  | resell    | —         | —             | high           | low    | 7      | Hosting Concepts B.V. d/b/a Registrar.eu |
| ava.london      | premium   | $680.21   | —             | high           | medium | 3      | name.com                                 |
| auld.london     | available | $12.98    | $41.98        | medium         | low    | 4      | namecheap                                |
| explore.london  | resell    | —         | —             | high           | medium | 7      | Namecheap                                |
| axe.london      | premium   | $679.48   | —             | high           | low    | 3      | name.com                                 |
| djia.london     | available | $31.99    | $31.99        | high           | low    | 4      | namesilo                                 |
| grocery.london  | resell    | —         | —             | high           | low    | 7      | BB Online UK Limited                     |
| boy.london      | premium   | $679.48   | —             | high           | low    | 3      | name.com                                 |
| eyry.london     | available | $12.98    | $41.98        | high           | low    | 4      | namecheap                                |
| bathroom.london | resell    | —         | —             | high           | low    | 8      | Porkbun, LLC                             |
| btw.london      | premium   | $681.70   | —             | high           | low    | 3      | name.com                                 |
| liii.london     | available | $12.98    | $41.98        | medium         | low    | 4      | namecheap                                |
| cap.london      | premium   | $676.56   | —             | high           | low    | 3      | name.com                                 |
| nyse.london     | available | $31.99    | $31.99        | high           | low    | 4      | namesilo                                 |
| clv.london      | premium   | $133.50   | $59.99        | high           | low    | 3      | name.com                                 |
| prat.london     | available | $12.98    | $41.98        | medium         | low    | 4      | namecheap                                |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 31,840 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 36 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/london?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/london?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection covers one-word .LONDON domain names — single-token names without hyphens or numbers, spanning wellness, lifestyle, and everyday-action phrases. Names such as flaxseed.london, gearup.london, and getlife.london show the compact, city-tied style common across this list. With a median asking price near $157, the set spans budget-friendly picks to higher-priced names, giving founders a shortlist to evaluate and giving investors a consistent pool to track pricing against.

- 11,697 one-word .LONDON domains in this selection
- Median asking price near $157 across the set
- Compound names like restassured.london stay short and memorable
- Updated daily for consistent pricing and inventory checks

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LONDON One-Word Domains*. Version 2026-09-25. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LONDON page](https://unique.domains/domains/tld/london?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
