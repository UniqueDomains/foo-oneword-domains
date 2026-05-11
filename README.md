# Available .FOO One-Word Domains (12,826)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C826%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .foo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,826 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,826 domains · **Median ask:** $82.75 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/foo`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/foo?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./foo.csv">CSV</a> / <a href="./foo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FOO search](https://unique.domains/domains/tld/foo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FOO search](https://unique.domains/domains/tld/foo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FOO one-word domain catalog.

### Files

- `foo.csv` — public CSV extract (1,000 rows)
- `foo.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/foo-oneword-domains/main/foo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| RedSox.foo        | available | $17.98    | —             | 72             | 60     | 7      | namecheap |
| insight.foo       | premium   | $311.25   | —             | 76             | 69     | 8      | name.com  |
| keepthechange.foo | available | $16.99    | —             | 46             | 59     | 15     | name.com  |
| regions.foo       | premium   | $73.75    | —             | 64             | 59     | 7      | name.com  |
| rekt.foo          | available | $16.99    | —             | 40             | 24     | 4      | name.com  |
| jobs.foo          | premium   | $1,248.75 | —             | 79             | 42     | 4      | name.com  |
| Allie.foo         | available | $17.98    | —             | 72             | 21     | 5      | namecheap |
| shortcuts.foo     | premium   | $73.75    | —             | 48             | 41     | 10     | name.com  |
| smartest.foo      | available | $16.99    | —             | 64             | 20     | 8      | name.com  |
| stories.foo       | premium   | $623.75   | —             | 58             | 36     | 7      | name.com  |
| outofoffice.foo   | available | $16.99    | —             | 61             | 19     | 13     | name.com  |
| tickets.foo       | premium   | $623.75   | —             | 64             | 34     | 7      | name.com  |
| intune.foo        | available | $16.99    | —             | 72             | 16     | 7      | name.com  |
| teams.foo         | premium   | $311.25   | —             | 62             | 32     | 5      | name.com  |
| calculators.foo   | available | $16.99    | —             | 54             | 16     | 11     | name.com  |
| inspiration.foo   | premium   | $73.75    | —             | 88             | 30     | 11     | name.com  |
| accountants.foo   | available | $16.99    | —             | 50             | 16     | 11     | name.com  |
| spaces.foo        | premium   | $623.75   | —             | 54             | 30     | 6      | name.com  |
| heavymetal.foo    | available | $16.99    | —             | 70             | 15     | 11     | name.com  |
| popup.foo         | premium   | $623.75   | —             | 84             | 29     | 6      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,826 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/foo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/foo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of one-word .foo domains. The names range from broad dictionary words such as active, audio, view, and major to more specific terms like vitamin and routine. For founders, the main question is whether the word is memorable, easy to say, and specific enough to support a brand without feeling narrow. For investors, the focus is cleaner entry pricing, buyer breadth, and whether the word has obvious commercial use. The median ask is 82.75, which keeps price comparison straightforward. Be careful with terms that may carry trademark exposure, especially exact matches to established brands such as Nickelodeon.

- One-word .foo names only, from broad to category-specific terms
- Median ask is 82.75 across this selection
- Stronger picks are simple, memorable, and commercially flexible
- Avoid exact-brand matches where trademark risk looks obvious

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FOO One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FOO page](https://unique.domains/domains/tld/foo?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_foo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
