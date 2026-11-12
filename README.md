# Graphify for TACITUS — historical integration fork

<!-- tacitus-practical-entry -->
## Purpose, code and a playable introduction

Evaluate code/document graph navigation as a way to understand a TACITUS module before changing it.

**Upstream evaluation fork.** Upstream Graphify fork. Extracted and inferred graph edges must remain distinct; no independent TACITUS retrieval-quality improvement is claimed.

[Setup, code walkthrough, research & verification](TACITUS_GUIDE.md) · [Play the original 8-bit teaching adventure](tacitus-demo/index.html) · [Demo credits](tacitus-demo/CREDITS.md)

![The original House of Evidence teaching adventure; synthetic case, separate from this project’s runtime](tacitus-demo/mansion.png)

Research: [RAG](https://arxiv.org/abs/2005.11401), [long-context evidence use](https://arxiv.org/abs/2307.03172), [GraphRAG](https://arxiv.org/abs/2404.16130). [What TACITUS borrows, adds and still needs to measure](https://github.com/sargonxg/sargonxg/blob/main/docs/RESEARCH_AND_DESIGN.md).
<!-- /tacitus-practical-entry -->


> **Status: completed experiment; no longer maintained.** This fork is retained for provenance and is not an active TACITUS release.

This repository was used in April 2026 to evaluate Graphify as a possible knowledge-graph layer for TACITUS. It remains a GitHub fork so that its relationship to the upstream code and commit history is clear.

For the maintained Graphify project, use [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify). No independent package or supported distribution is published from this fork.

## Why it remains public

- to preserve the exact upstream state used during the TACITUS evaluation;
- to retain any experimental integration changes in their original history;
- to document an architectural path that was considered but not adopted as a standalone TACITUS product.

Current TACITUS development is centered on [DIALECTICA](https://github.com/sargonxg/A3_DIALECTICAbyTACITUS_v3), the [Tacitus Policy Workbench](https://github.com/sargonxg/tacitus-political-policy-second-brain), and [TCGC](https://github.com/sargonxg/TCGC_TACITUS-Conflict-Grammar-Corpus_BENCHMARK).

## Attribution and license

Graphify is the work of its upstream maintainers and contributors. See the fork relationship, repository history, and [LICENSE](LICENSE) for attribution and applicable terms.
