# Available .PROMO One-Word Domains (17,268)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C268%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .promo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,268 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,268 domains · **Median ask:** $82.85 · **High-demand under $2,500:** 1

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/promo`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/promo?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./promo.csv">CSV</a> / <a href="./promo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PROMO search](https://unique.domains/domains/tld/promo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PROMO search](https://unique.domains/domains/tld/promo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PROMO one-word domain catalog.

### Files

- `promo.csv`, public CSV extract (1,000 rows)
- `promo.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/promo-oneword-domains/main/promo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| abo.promo   | available | $11.98    | $33.48        | low            | low    | 3      | namecheap                                    |
| bit.promo   | resell    | —         | —             | high           | medium | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| art.promo   | premium   | $1,300    | $1,300        | high           | medium | 3      | namecheap                                    |
| ana.promo   | available | $19.99    | —             | high           | low    | 3      | name.com                                     |
| fast.promo  | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC                                 |
| ink.promo   | premium   | $1,107    | $1,107        | high           | medium | 3      | namesilo                                     |
| ass.promo   | available | $11.98    | $33.48        | low            | low    | 3      | namecheap                                    |
| view.promo  | resell    | —         | —             | high           | low    | 4      | NameSilo, LLC                                |
| lie.promo   | premium   | $1,107    | $1,107        | medium         | low    | 3      | namesilo                                     |
| ate.promo   | available | $19.99    | —             | high           | low    | 3      | name.com                                     |
| color.promo | resell    | —         | —             | high           | low    | 5      | IONOS SE                                     |
| tie.promo   | premium   | $1,875    | —             | high           | low    | 3      | name.com                                     |
| beg.promo   | available | $19.99    | —             | medium         | low    | 3      | name.com                                     |
| crazy.promo | resell    | —         | —             | high           | low    | 5      | Dynadot Inc                                  |
| usa.promo   | premium   | $3,125    | —             | high           | medium | 3      | name.com                                     |
| con.promo   | available | $19.99    | —             | high           | low    | 3      | name.com                                     |
| nurse.promo | resell    | —         | —             | medium         | low    | 5      | IONOS SE                                     |
| wow.promo   | premium   | $1,107    | $1,107        | high           | medium | 3      | namesilo                                     |
| end.promo   | available | $19.99    | —             | high           | low    | 3      | name.com                                     |
| print.promo | resell    | —         | —             | high           | medium | 5      | Virtualia LLC                                |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,268 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 1 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/promo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/promo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=related_pricing)

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

This set of one-word .promo domain names spans everyday vocabulary, seasonal terms, and short emotional phrases — from half.promo and okay.promo to christmas.promo and sorry.promo. With 12,248 domains and a median ask near $131, .promo offers an affordable way to secure a short, memorable name for a promotion, sale, or campaign-driven brand. When comparing these domains, weigh brandability against renewal cost and how well the word fits a promo-driven use case.

- 12,248 one-word .promo domain names in this selection
- Median ask near $131 across the set
- Mix of everyday words, holidays, and emotional terms
- Short, ownable names suited for promos and campaigns

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PROMO One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PROMO page](https://unique.domains/domains/tld/promo?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_promo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
