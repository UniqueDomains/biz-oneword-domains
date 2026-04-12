# Available .BIZ One-Word Domains (6,525)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-6%2C525%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-6%2C525%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .biz one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 6,525 rows · **Live catalog:** 6,525 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/biz`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/biz?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./biz.csv">CSV</a> / <a href="./biz.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BIZ search](https://unique.domains/domains/tld/biz?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BIZ search](https://unique.domains/domains/tld/biz?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BIZ one-word domain catalog.

### Files

- `biz.csv` — public CSV extract (6,525 rows)
- `biz.json` — public JSON extract (6,525 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/biz-oneword-domains/main/biz.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| allout.biz     | available | $24.98    | —             | 84             | 9      | 7      | namecheap       |
| clear.biz      | resell    | $5,750    | $20           | 90             | 49     | 5      | Sav.com LLC     |
| seventeen.biz  | premium   | $31.25    | $20           | 84             | 62     | 9      | name.com        |
| contingent.biz | available | $24.98    | —             | 80             | 9      | 10     | namecheap       |
| land.biz       | resell    | $316,250  | $29.99        | 62             | 36     | 4      | Spaceship, Inc. |
| athletics.biz  | premium   | $218.75   | $20           | 69             | 52     | 9      | name.com        |
| eighth.biz     | available | $9.99     | $29.99        | 100            | 7      | 6      | name.com        |
| robotic.biz    | resell    | $1,840    | $20           | 72             | 30     | 7      | Sav.com LLC     |
| unity.biz      | premium   | $6,250    | $20           | 70             | 40     | 5      | name.com        |
| costly.biz     | available | $24.98    | —             | 66             | 7      | 6      | namecheap       |
| choose.biz     | resell    | $1,148.85 | $20           | 102            | 26     | 6      | Porkbun         |
| shared.biz     | premium   | $218.75   | $20           | 70             | 39     | 6      | name.com        |
| nought.biz     | available | $24.98    | —             | 92             | 6      | 6      | namecheap       |
| define.biz     | resell    | $31.25    | $20           | 96             | 21     | 6      | Spaceship, Inc. |
| streaming.biz  | premium   | $6,250    | $20           | 88             | 35     | 9      | name.com        |
| derelict.biz   | available | $24.98    | —             | 92             | 6      | 8      | namecheap       |
| abroad.biz     | resell    | $1,481.20 | $29.99        | 92             | 14     | 6      | NameSilo, LLC   |
| goon.biz       | premium   | $62.50    | $20           | 80             | 35     | 5      | name.com        |
| tenner.biz     | available | $24.98    | —             | 66             | 6      | 6      | namecheap       |
| decade.biz     | resell    | $862.50   | $29.99        | 82             | 13     | 6      | Sav.com LLC     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 6,525-row public sample | 6,525 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/biz?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/biz?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .BIZ One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BIZ page](https://unique.domains/domains/tld/biz?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
