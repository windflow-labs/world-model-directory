# Contributing

Open a pull request editing `models.json`. A new entry must have published weights, a public demo or a public API. It also needs an official project, paper or model-card URL, a stable lowercase kebab-case ID, a short control description and a source-review date. Keep entries and providers alphabetical. Preserve separate releases when the license or capabilities change.

For a license change, link the exact weight model card and license text. Do not infer weight permission from a code repository badge. If sources conflict, keep the conflict visible and explain it. For realtime claims, cite a model-specific author statement; measured latency requires reproducible methodology, exact revision and settings before inclusion. Do not turn throughput into an interaction-latency claim.

For a hosted destination, link the model-specific page and identify any access or version caveat. A general provider catalog belongs in `providers`, not every model's `tryAt` list. No affiliate links, promotional ranking, unverifiable superlatives or paid placement.

Check JSON validity and the `schema.json` contract in your editor. IDs must be unique. Every entry needs at least one primary source. Keep summaries in English, update only dates you actually reviewed, and explain evidence changes in the pull request. Unknown fields should remain explicitly unverified.

Optional page fields (`organization`, `released`, `summary`, `controlsDetail`, `realtimeDetail`) feed the model pages on windflow.online/world-models. Write them from primary sources only, keep the summary to two or three factual sentences, and give real-time figures without hardware names.
