# Available .BIZ One-Word Domains (8,715)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C715%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .biz one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **8,715 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 8,715 domains

**Last updated:** 2026-04-27  
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

- `biz.csv` — public CSV extract (1,000 rows)
- `biz.json` — public JSON extract (1,000 rows)
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

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                    |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------- |
| keepthechange.biz | available | $1.99     | —             | 46             | 59     | 15     | name.com                     |
| farmers.biz       | resell    | —         | —             | 54             | 59     | 7      | Moniker Online Services, LLC |
| pops.biz          | premium   | $53.92    | $21.24        | 74             | 24     | 4      | namesilo                     |
| saveit.biz        | available | $1.99     | —             | 74             | 13     | 7      | name.com                     |
| tokens.biz        | resell    | —         | —             | 51             | 36     | 6      | GoDaddy.com, LLC             |
| superhero.biz     | premium   | $31.99    | —             | 84             | 23     | 9      | name.com                     |
| forces.biz        | available | $1.99     | —             | 82             | 12     | 6      | name.com                     |
| homes.biz         | resell    | —         | —             | 86             | 34     | 5      | GoDaddy.com, LLC             |
| machines.biz      | premium   | $1,250    | —             | 56             | 22     | 8      | name.com                     |
| extras.biz        | available | $1.99     | —             | 56             | 11     | 6      | name.com                     |
| commonsense.biz   | resell    | —         | —             | 86             | 30     | 12     | 101domain GRS Limited        |
| smartest.biz      | premium   | $29.50    | $21.24        | 64             | 20     | 8      | namesilo                     |
| playin.biz        | available | $1.99     | —             | 80             | 10     | 7      | name.com                     |
| cams.biz          | resell    | —         | —             | 52             | 29     | 4      | eNom, LLC                    |
| workers.biz       | premium   | $31.99    | —             | 60             | 20     | 7      | name.com                     |
| equals.biz        | available | $1.99     | —             | 62             | 10     | 6      | name.com                     |
| dogs.biz          | resell    | —         | —             | 76             | 28     | 4      | GoDaddy.com, LLC             |
| engineers.biz     | premium   | $218.75   | —             | 60             | 19     | 9      | name.com                     |
| breaks.biz        | available | $1.99     | —             | 52             | 10     | 6      | name.com                     |
| gems.biz          | resell    | —         | —             | 70             | 28     | 4      | GoDaddy.com, LLC             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 8,715 live domains                               |
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

> Unique Domains. *Available .BIZ One-Word Domains*. Version 2026-04-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BIZ page](https://unique.domains/domains/tld/biz?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
