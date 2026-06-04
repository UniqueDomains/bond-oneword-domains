# Available .BOND One-Word Domains (10,668)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C668%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .bond one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,668 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,668 domains · **Median ask:** $46.14 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
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

- `bond.csv` — public CSV extract (1,000 rows)
- `bond.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/bond-oneword-domains/main/bond.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar            |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------- |
| checklist.bond    | premium   | $43.66    | $88.06        | 88             | 23     | 9      | namesilo             |
| easy.bond         | premium   | $552.19   | $736.25       | 128            | 62     | 4      | name.com             |
| key.bond          | resell    | —         | —             | 80             | 42     | 3      | Dominet (HK) Limited |
| lyrics.bond       | premium   | $384      | $768          | 90             | 20     | 6      | namesilo             |
| acute.bond        | available | $1.88     | $14.95        | 112            | 12     | 5      | namesilo             |
| grin.bond         | resell    | —         | —             | 102            | 25     | 4      | Dominet (HK) Limited |
| headup.bond       | available | $2.49     | —             | 80             | 5      | 7      | name.com             |
| ben.bond          | premium   | $87.47    | $188.16       | 84             | 49     | 3      | namesilo             |
| yearly.bond       | premium   | $188.16   | $376.32       | 104            | 8      | 6      | namesilo             |
| consensus.bond    | available | $1.88     | $14.95        | 92             | 26     | 9      | namesilo             |
| airplane.bond     | premium   | $43.66    | $88.06        | 91             | 15     | 8      | namesilo             |
| country.bond      | premium   | $188.16   | $376.32       | 92             | 28     | 7      | namesilo             |
| souse.bond        | premium   | —         | —             | 84             | 3      | 5      | —                    |
| intensive.bond    | premium   | $43.66    | $88.06        | 82             | 6      | 9      | namesilo             |
| fold.bond         | premium   | $21.83    | $43.66        | 96             | 21     | 4      | namesilo             |
| bouncing.bond     | available | $1.88     | $14.95        | 90             | 6      | 8      | namesilo             |
| fatigue.bond      | available | $1.88     | $14.95        | 88             | 10     | 7      | namesilo             |
| freespirit.bond   | premium   | $43.66    | $88.06        | 82             | 16     | 11     | namesilo             |
| IndianaJones.bond | available | $2.49     | —             | 80             | 5      | 13     | name.com             |
| conduction.bond   | available | $1.88     | $14.95        | 84             | 4      | 10     | namesilo             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,668 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/bond?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/bond?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .bond domains. The naming style ranges from direct dictionary cues to short, action-oriented words and softer brandable terms, as seen in finals.bond, geton.bond, playon.bond, and edamame.bond. For founders, the key question is whether the word stays memorable and credible once paired with .bond. For investors, the main test is whether the keyword has enough clarity or commercial relevance to support resale interest. Median ask is 34.89, which keeps attention on word quality, extension fit, and renewal discipline rather than headline price alone.

- All results use the .bond extension
- One-word mix of literal and brandable terms
- Median ask across this set is 34.89
- Check word clarity, fit, and renewal risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BOND One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BOND page](https://unique.domains/domains/tld/bond?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bond_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
