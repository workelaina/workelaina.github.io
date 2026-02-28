---
title: "TBO: Towards Stealthy Black-box Adversarial Attacks against RAG-Based LLMs"
collection: publications
permalink: /publication/tbo
# excerpt: 'This paper is about fixing template issue #693.'
date: 1970-01-03
venue: 'Unpublished'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Keywords: LLM, RAG, Adversarial Attack, Black-box.

Abstract:

Retrieval-Augmented Generation (RAG) is recognized as an effective strategy for enhancing the reliability of text generation in Large Language Models (LLMs). However, RAG introduces potential security vulnerabilities wherein subtle input perturbations can significantly impact the output of RAG-based LLMs. Existing adversarial attacks on RAG-based LLMs typically require numerous queries and white-box access to model internals, which substantially deviates from practical deployment scenarios. Moreover, they often generate linguistically inconsistent content, which makes the attacks easier to detect. To address these challenges, we propose a stealthy and query-efficient black-box adversarial attack based on Bayesian optimization, referred to as the Token-wise Bayesian Optimization (TBO), which targets the retriever and manipulates the LLM’s acquired knowledge, causing it to generate inaccurate responses. TBO incorporates a categorical kernel with automatic relevance determination, where each token's scale length parameter serves as its importance score and is adaptively updated through historical observations. This mechanism enables precise control over the number of perturbed tokens, allowing targeted synonym substitution at a specified quantity of carefully selected positions while preserving semantic coherence. Extensive experimental results demonstrate that TBO consistently achieves superior attack success rates against RAG-based LLMs. Compared to existing state-of-the-art methods, TBO significantly reduces both the required number of queries and the rate of token modifications.

BibTeX:

```bibtex
@
```
