<p align="center">
  <img src="assets/readme/brand.png#gh-light-mode-only" width="480" alt="Noumena Evaluation">
  <img src="assets/readme/brand-dark.png#gh-dark-mode-only" width="480" alt="Noumena Evaluation">
</p>

<p align="center">
  <a href="README.md">简体中文</a> · <strong>English</strong>
</p>

<p align="center">
  Noumena’s open collection of benchmarks for marketing judgment.<br>
  This page is the index. Each benchmark is its own volume.
</p>

<p align="center">
  <a href="https://github.com/Noumena-Marketing-AI/noumena-evaluation/stargazers"><img src="https://img.shields.io/github/stars/Noumena-Marketing-AI/noumena-evaluation?style=flat-square&color=A68456" alt="GitHub Stars"></a>
  <img src="https://img.shields.io/badge/Published-1-16130F?style=flat-square" alt="1 benchmark published">
</p>

<p align="center">
  <a href="#noumena">Noumena</a>
  &nbsp;·&nbsp;
  <a href="#the-collection">The collection</a>
  &nbsp;·&nbsp;
  <a href="#index">Index</a>
  &nbsp;·&nbsp;
  <a href="#layout">Layout</a>
</p>

![Noumena Evaluation. This page is the index. Each benchmark is its own volume.](assets/readme/frontispiece-en.png)

<a id="noumena"></a>

## Noumena

Noumena was founded in 2023. It works on Growth Intelligence: agents for marketing decisions, and for the work that follows them. The team mixes AI research, engineering, and people who still do the marketing. The aim is to turn insight, content, creator work, media, and postmortems into a system that can learn.

Public mail: [hello@noumena.com.cn](mailto:hello@noumena.com.cn)

<a id="the-collection"></a>

## The collection

Noumena Evaluation publishes benchmarks of marketing judgment. It is not the homepage of any one board.

Each benchmark asks its own question, and keeps its own tasks, criteria, and results. This README says who the collection is, which volumes exist, and where to read them. Method, scores, cases, and how to join live in that benchmark’s own document.

When a new benchmark is added, this page gains one brief. Published volumes are not rewritten here.

<a id="index"></a>

## Index

| No. | Benchmark | The question | Volume |
| --- | --- | --- | --- |
| 01 | [CMO Bench](benchmarks/cmo-bench/README_EN.md) | Can a model judge marketing work to a CMO-level standard? | [English](benchmarks/cmo-bench/README_EN.md) · [中文](benchmarks/cmo-bench/README.md) |

### 01 · CMO Bench

<a href="benchmarks/cmo-bench/README_EN.md">
  <img src="assets/readme/catalog-cmo-en.jpg" width="100%" alt="CMO Bench brief: nearly perfect at execution, only half right at the call. Expert adoption 41.1%. 56 real tasks. The leading model spent ¥446.">
</a>

Built by Noumena with Professor Yangqiu Song’s KnowComp group at the Hong Kong University of Science and Technology. It is the first volume in this collection. A CMO-level expert, with more than ten years in the field, wrote the criteria by hand after doing the work. The tasks come from real engagements with leading brands, then desensitized and rewritten.

One line from the first release: nearly perfect at execution, only half right at the call.

[Read CMO Bench](benchmarks/cmo-bench/README_EN.md) · [中文](benchmarks/cmo-bench/README.md) · [Board](https://solution.alphacat.pro/cmo-bench-hkust)

<a id="layout"></a>

## Layout

```text
README.md                          collection index, Chinese default
README_EN.md                       collection index, English
benchmarks/<bench>/README.md       that benchmark, in Chinese
benchmarks/<bench>/README_EN.md    that benchmark, in English
benchmarks/<bench>/assets/         images for that volume only
```

To add a benchmark, create `benchmarks/<bench>/`, then add one brief to the index above. Do not put the new method, board, or cases into the root README.

## Contact

Write to [hello@noumena.com.cn](mailto:hello@noumena.com.cn). Name the benchmark and your role in the subject. How to join is stated in that volume.

## Citation

```text
Noumena. Noumena Evaluation.
2026.
https://github.com/Noumena-Marketing-AI/noumena-evaluation
```
