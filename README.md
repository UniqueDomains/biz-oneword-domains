# Available .BIZ One-Word Domains (8,926)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C926%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .biz one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **8,926 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 8,926 domains · **Median ask:** $158.67 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
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

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar               |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------- |
| consuming.biz        | premium   | $31.25    | $20           | 82             | 3      | 9      | name.com                |
| defence.biz          | premium   | $218.75   | —             | 90             | 22     | 7      | name.com                |
| meanwhile.biz        | premium   | $29.50    | $21.24        | 80             | 15     | 9      | namesilo                |
| generalknowledge.biz | available | $7.99     | $23.49        | 80             | 4      | 17     | namesilo                |
| iron.biz             | resell    | —         | —             | 84             | 30     | 4      | Sav.com LLC             |
| fine.biz             | resell    | —         | —             | 80             | 28     | 4      | eNom, LLC               |
| variable.biz         | premium   | $29.50    | $21.24        | 80             | 17     | 8      | namesilo                |
| mature.biz           | resell    | —         | —             | 92             | 16     | 6      | Inames Co. Ltd.         |
| uncle.biz            | resell    | —         | —             | 114            | 17     | 5      | Wild West Domains, Inc. |
| overtime.biz         | resell    | —         | —             | 94             | 15     | 8      | Spaceship, Inc.         |
| award.biz            | resell    | —         | —             | 104            | 21     | 5      | Spaceship, Inc.         |
| experimental.biz     | premium   | $29.50    | $21.24        | 80             | 19     | 12     | namesilo                |
| mechanical.biz       | resell    | —         | —             | 84             | 16     | 10     | Sav.com, LLC - 4        |
| corrupt.biz          | premium   | $218.75   | $20           | 80             | 13     | 7      | name.com                |
| pink.biz             | resell    | —         | —             | 89             | 34     | 4      | Dynadot Inc             |
| economy.biz          | resell    | —         | —             | 104            | 23     | 7      | Dynadot Inc             |
| midFebruary.biz      | available | $11.99    | —             | 98             | 1      | 12     | name.com                |
| shot.biz             | premium   | $53.92    | $21.24        | 116            | 24     | 4      | namesilo                |
| duplicate.biz        | premium   | $31.25    | $20           | 100            | 7      | 9      | name.com                |
| count.biz            | premium   | $302.50   | $21.24        | 122            | 20     | 5      | namesilo                |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 8,926 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This set is entirely focused on .biz domain names. The range includes dictionary-style words such as finals.biz and forces.biz, more suggestive combinations such as toneup.biz and beawake.biz, and some names that raise obvious trademark concerns, such as Netflix.biz. For founders, the main question is whether a .biz ending still feels credible for the brand you want to build. For investors, the key is whether the word quality justifies the extension. With a median ask of 205.015182, pricing is relatively accessible, so selection quality matters more than chasing small differences in ask.

- All results in this set use the .biz extension
- Median ask across the selection is 205.015182
- Word quality varies from clean to awkward or risky
- Check trademark exposure before valuing any name

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BIZ One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BIZ page](https://unique.domains/domains/tld/biz?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_biz_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
