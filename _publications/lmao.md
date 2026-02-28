---
title: "Three Forward, One Backward: Memory-Efficient Full-Rank Fine-Tuning of Large Models via Extra Forward Passes"
collection: publications
permalink: /publication/lmao
# excerpt: 'This paper is about fixing template issue #693.'
date: 2026-04-27
venue: 'ICLR (Poster)'
paperurl: 'https://workelaina.github.io/LMAO/static/blob/LMAO.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Three Forward, One Backward: Memory-Efficient Full-Rank Fine-Tuning of Large Models via Extra Forward Passes.

Jia Zhang, [Yu Bai](https://workelaina.github.io/), Hualin Zhang, Tianshuo Chen, Zhaogeng Liu, Zhiqiang Xu, [Yi Chang](http://www.yichang-cs.com/), [Bin Gu](https://scholar.google.com/citations?user=Vo8OgCgAAAAJ).

[[ICLR 2026](https://iclr.cc/Conferences/2026)]
[[OpenReview](https://openreview.net/forum?id=373rsDQsq4)]
[[Homepage](https://workelaina.github.io/LMAO)]
[[PDF](https://workelaina.github.io/LMAO/static/blob/LMAO.pdf)]
[[Code](https://github.com/workelaina/LMAO)]

Keywords: LLM Tuning, LoRA, Zero-order, Machine Learning, Optimization.

Abstract:

Fine-tuning large language models (LLMs) has achieved significant success in downstream tasks. However, as the model size continues to grow, traditional fine-tuning methods have become increasingly impractical due to their high computational and memory costs. This has motivated researchers to explore parameter-efficient and memory-friendly fine-tuning strategies to enable scalable approaches, with Low-Rank Adaptation (LoRA) standing out as a representative work. However, the LoRA update is restricted to a low-rank subspace, which results in suboptimal performance compared to the full-parameter update. Recent research has also explored memory-efficient fine-tuning LLMs using just forward passes while suffer from high variance in gradient estimation and low convergence speed. To address the issues above, we propose a new alternating optimization framework called LMAO (**L**ow-rank and **M**emory-efficient Zeroth-Order **A**lternating **O**ptimization), which combines the advantages of LoRA and MeZO. This method alternately updates the low-rank components and zeroth-order directions during training. By performing three forward propagations and one backward propagation, each update is full-rank, thereby reducing feature loss and enabling efficient fine-tuning under strict memory constraints. We provide theoretical guarantees on the convergence and convergence rate of this method. Empirical results demonstrate that, in experiments on multiple models (e.g., OPT, RoBERTa-large), LMAO achieves performance comparable to first-order methods. This presents a practical and scalable solution for fine-tuning large-scale models.

BibTeX:

```latex
@
```
