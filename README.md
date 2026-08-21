# Available .BOND One-Word Domains (15,688)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C688%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .bond one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,688 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,688 domains · **Median ask:** $38.34 · **High-demand under $2,500:** 47

**Last updated:** 2026-08-21
**Canonical page:** `https://unique.domains/domains/tld/bond`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/bond?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./bond.csv">CSV</a> / <a href="./bond.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BOND search](https://unique.domains/domains/tld/bond?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BOND search](https://unique.domains/domains/tld/bond?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BOND one-word domain catalog.

### Files

- `bond.csv`, public CSV extract (1,000 rows)
- `bond.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/bond-oneword-domains/main/bond.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar            |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------- |
| acerb.bond | available | $2        | $25.98        | low            | low    | 5      | namecheap            |
| bio.bond   | resell    | —         | —             | high           | medium | 3      | Dominet (HK) Limited |
| apt.bond   | premium   | $102.90   | $205.80       | high           | low    | 3      | namecheap            |
| acute.bond | available | $1.88     | $14.95        | high           | low    | 5      | namesilo             |
| bot.bond   | resell    | —         | —             | high           | medium | 3      | Dominet (HK) Limited |
| bce.bond   | premium   | $376.96   | $753.92       | medium         | low    | 3      | namesilo             |
| afoot.bond | available | $2        | $25.98        | low            | low    | 5      | namecheap            |
| cut.bond   | resell    | —         | —             | high           | low    | 3      | Dominet (HK) Limited |
| ben.bond   | premium   | $87.47    | $188.16       | high           | medium | 3      | namesilo             |
| amuse.bond | available | $1.88     | $14.95        | high           | low    | 5      | namesilo             |
| ivy.bond   | resell    | —         | —             | high           | low    | 3      | Dominet (HK) Limited |
| cxx.bond   | premium   | $68.43    | $147.20       | low            | low    | 3      | namesilo             |
| arced.bond | available | $2        | $25.98        | low            | low    | 5      | namecheap            |
| key.bond   | resell    | —         | —             | medium         | medium | 3      | Dominet (HK) Limited |
| DJI.bond   | premium   | $376.96   | $753.92       | high           | low    | 3      | namesilo             |
| auric.bond | available | $2        | $25.98        | low            | low    | 5      | namecheap            |
| map.bond   | resell    | —         | —             | high           | medium | 3      | Dominet (HK) Limited |
| far.bond   | premium   | $376.96   | $753.92       | high           | low    | 3      | namesilo             |
| axial.bond | available | $1.88     | $14.95        | high           | low    | 5      | namesilo             |
| opt.bond   | resell    | —         | —             | medium         | low    | 3      | Dominet (HK) Limited |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,688 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 47 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/bond?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/bond?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=related_pricing)

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

This list of .bond domains covers 10,672 one-word names, from everyday nouns like watches.bond and worm.bond to playful compounds like cuddleup.bond and coffeebush.bond. The median ask sits near $43, and the vast majority price under $500, making this an accessible entry point for founders shortlisting a brandable name and for investors scanning volume at low cost. A smaller share carries premium or resale pricing, so comparing ask price against renewal and demand signals helps separate everyday picks from standout names.

- 10,672 one-word .bond domains, median ask ~$43
- 9,559 domains priced under $500 — low-cost entry
- 8,072 available, 2,384 premium, 216 resell listings
- 6,519 domains rated easy to spell for brand recall

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BOND One-Word Domains*. Version 2026-08-21. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BOND page](https://unique.domains/domains/tld/bond?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
