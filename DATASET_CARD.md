---
pretty_name: Windflow World Model Directory
license: cc0-1.0
language:
- en
size_categories:
- n<1K
task_categories:
- other
tags:
- world-models
- video-generation
- model-directory
configs:
- config_name: default
  data_files:
  - split: train
    path: exports/models.csv
---
# Windflow World Model Directory

A source-linked directory maintained by Windflow Labs, a model-hosting provider. This release packages 56 entries from the November 3, 2026 source snapshot. The packaging date is November 9. It is a directory of published facts, not a benchmark, leaderboard or training corpus.

## Sources and collection

Editors summarize official model repositories, project pages, papers and selected weight model cards. Each row retains source URLs and the last review date. Entries and providers are alphabetical. Windflow appears under the same inclusion rules as other providers. The canonical editable source is https://github.com/windflow-labs/world-model-directory . Corrections should be proposed there before mirrors are updated.

## Data structure

`models.json` contains nested source and hosted-destination records. `exports/models.csv` contains the same 56 entries with flat columns. The name `train` is the loader's single-table split; no training/evaluation partition or fitness for model training is implied.

| Column | Meaning |
| --- | --- |
| id, name, organization, released | Stable directory ID, model/release name and selected publication metadata |
| category, summary, controls | Task category and short source-based descriptions |
| weights, weightsUrl | Published weight access and model-card destination |
| weightLicense, commercial, licenseNote | Selected weight license declaration, classified terms and context |
| realtime, measurement | Author realtime claim and explicit measurement boundary |
| sources | JSON array of primary-source labels and URLs |
| tryAt | JSON array of observed hosting destinations and caveats |
| checkedAt | Date this row's sources were reviewed |

Blank optional CSV fields mean no value was recorded. `Unverified` is an evidence gap, not proof of an absent capability. Read `schema.json` for enum meanings and constraints.

## Intended use and limits

Use the table for model discovery, factual comparison and linking readers to primary sources. Source terms and model versions can change after review. Code and weight licenses can differ. A listed provider page does not establish live capacity, unrestricted access or a matching model version. Generated video, spatial-world generation and robot simulation are different tasks. No entry has been independently measured for this directory, and author speed claims are not comparable benchmark results.

The sample reflects maintainer discovery and the inclusion rule requiring published weights, a public demo or a public API. It is not an exhaustive survey. Windflow's commercial role is disclosed so users can assess potential selection bias.

## Reuse and attribution

The original compilation and original factual summaries are offered under CC0 1.0. Linked models, source documents, weights, trademarks and third-party data retain their own terms. No linked weights or copied source documents are included here.

Suggested citation: Windflow Labs, World Model Directory, source snapshot 2026-11-03, packaging release v2026.11.09, https://github.com/windflow-labs/world-model-directory . `snapshot.json` records file hashes; `CITATION.cff` provides citation metadata.
