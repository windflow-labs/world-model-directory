# World Model Directory

A source-linked directory of world models maintained by Windflow. The directory contains 51 entries spanning interactive video, navigation, games, driving, robotics and spatial worlds. Entries and providers are alphabetical, with no scores, sponsored placement or preferred hosting provider.

An entry needs at least one way to run or try the model: published weights, a public demo or a public API. Research announcements with none of these stay out until one exists, and withdrawn or empty weight repositories do not count.

- `models.json`: the editable dataset.
- `schema.json`: JSON Schema (2020-12) describing the data contract.
- `CONTRIBUTING.md`: how to submit additions and corrections.

## Methodology

Each entry identifies its source, the selected weight release when verified, supported controls, weight-license declarations, author realtime claims, hosted destinations and source-review date. A source review is not a benchmark or service availability test. No entry has been independently measured for this directory. Existing measurements from other projects have not been imported because their settings are not necessarily comparable.

“Permissive license declared” records the model card's statement; it does not resolve all dependencies, content rights or use-specific conditions. “Conflicting sources” retains disagreements between model-card metadata and project documentation. Code licenses are never substituted for weight licenses. “Unverified” is an evidence gap, not a negative capability assertion. A public weight card may still require authentication or agreement to terms for downloads.

“Author claim” means the cited project describes realtime operation. It does not mean equal latency across models. Spatial world creation, latent prediction and live video generation are distinct tasks. Versioned releases are separate entries when their capabilities or terms differ.

“Where to try” links point to observed provider pages, not guaranteed running capacity. Provider pages may have different model versions or interaction modes; follow the endpoint documentation. HTTP errors are excluded from the first snapshot's destination list. The general provider list is not a claim that every provider hosts every model.

## Ownership and updating

Windflow maintains this dataset and is also a hosting provider. It appears under the same inclusion rules as other providers. External model authors own their models and documentation. This repository contains short factual summaries and links, not copied documentation or weights.

Corrections arrive as pull requests. Maintainers review primary sources before updating the date or publishing a new snapshot. There is no automated refresh or promised release cadence yet. The website consumes a checked-in snapshot so a third-party submission cannot change the website without review.

## Data reuse

The original factual compilation and original text in this repository are offered under CC0 1.0: https://creativecommons.org/publicdomain/zero/1.0/. This does not license any linked models, weights, datasets, trademarks or source documents.
