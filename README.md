# Available .LONDON One-Word Domains (11,695)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C695%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .london one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,695 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,695 domains · **Median ask:** $129.62 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `london.csv` — public CSV extract (1,000 rows)
- `london.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/london-oneword-domains/main/london.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------------------- |
| regions.london      | available | $41.98    | —             | 64             | 59     | 7      | namecheap                                |
| apartments.london   | resell    | —         | —             | 60             | 21     | 10     | Hosting Concepts B.V. d/b/a Registrar.eu |
| farmers.london      | premium   | $67.66    | —             | 54             | 59     | 7      | name.com                                 |
| prompts.london      | available | $31.99    | $31.99        | 54             | 39     | 7      | namesilo                                 |
| Cats.london         | premium   | $755.58   | $37.79        | 59             | 33     | 4      | namecheap                                |
| teams.london        | available | $41.98    | —             | 62             | 32     | 5      | namecheap                                |
| William.london      | premium   | $151.12   | $37.79        | 74             | 31     | 7      | namecheap                                |
| solutions.london    | available | $41.98    | —             | 56             | 31     | 9      | namecheap                                |
| SanDiego.london     | premium   | $64.43    | $31.94        | 74             | 29     | 9      | namesilo                                 |
| rewards.london      | available | $31.99    | $31.99        | 62             | 30     | 7      | namesilo                                 |
| dogs.london         | premium   | $676.64   | —             | 76             | 28     | 4      | name.com                                 |
| heroes.london       | available | $41.98    | —             | 68             | 29     | 6      | namecheap                                |
| pages.london        | premium   | $135.32   | —             | 52             | 28     | 5      | name.com                                 |
| quotes.london       | available | $41.98    | —             | 58             | 29     | 6      | namecheap                                |
| backyard.london     | premium   | $135.32   | —             | 80             | 27     | 9      | name.com                                 |
| commonground.london | available | $41.98    | —             | 74             | 28     | 13     | namecheap                                |
| bees.london         | premium   | $135.34   | —             | 54             | 27     | 4      | name.com                                 |
| Trex.london         | available | $41.98    | —             | 80             | 24     | 5      | namecheap                                |
| traders.london      | premium   | $135.01   | —             | 60             | 26     | 7      | name.com                                 |
| deeplearning.london | available | $41.98    | —             | 74             | 23     | 13     | namecheap                                |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,695 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/london?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/london?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=related_pricing)

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

These domains are all one-word names on the .london extension. The set leans toward dictionary-style words such as striking.london, survey.london, detour.london, and suppose.london, which can suit local brands, campaigns, publications, or service businesses that want a London-specific identity. When comparing these domains, focus first on whether the word is easy to say, easy to spell, and strong enough to carry a brand on its own. Then weigh ask price against how commercially usable the word feels. Generic, clear words can be easier to justify, while awkward or negative words may be cheaper but harder to build around.

- All results are one-word names on the .london extension
- Median ask pricing is 129.62 across this selection
- Favor clear, memorable words with local brand potential
- Be cautious with negative or weak terms like worse.london

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LONDON One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LONDON page](https://unique.domains/domains/tld/london?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_london_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
