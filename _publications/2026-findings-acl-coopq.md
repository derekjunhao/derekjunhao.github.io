---
title: "CoopQ: Cooperative Game Inspired Layerwise Mixed Precision Quantization for LLMs"
collection: publications
permalink: /publication/2026-findings-acl-coopq
date: 2026-07-01
venue: "Findings of the Association for Computational Linguistics: ACL 2026"
paperurl: "https://aclanthology.org/2026.findings-acl.373.pdf"
citation: "Junchen Zhao, Ali Derakhshan, Jayden Hyman, Junhao Dong, Sangeetha Abdu Jyothi, and Ian Harris. (2026). &quot;CoopQ: Cooperative Game Inspired Layerwise Mixed Precision Quantization for LLMs.&quot; <i>Findings of the Association for Computational Linguistics: ACL 2026</i>, pages 7566–7578."
---

<a href="https://aclanthology.org/2026.findings-acl.373/"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i> ACL Anthology</a> | <a href="https://doi.org/10.18653/v1/2026.findings-acl.373"><i class="fas fa-fw fa-external-link-alt zoom" aria-hidden="true"></i> DOI: 10.18653/v1/2026.findings-acl.373</a> | <a href="https://aclanthology.org/2026.findings-acl.373.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i> Download PDF</a>

### Abstract
Post-training mixed-precision quantization helps compress large language models for resource-constrained environments, but aggressive sub-4-bit compression often degrades output quality when relying on isolated per-layer metrics[cite: 1]. This work frames layer selection as a cooperative game, introducing Shapley-based Progressive Quantization Estimation (SPQE) to measure both individual layer sensitivity and cross-layer interactions[cite: 1]. These estimates are incorporated into a binary quadratic optimization objective (CoopQ) to assign 2- or 4-bit precision under set memory budgets[cite: 1]. Evaluated across model architectures including Llama-3, Gemma-2, and Qwen with multiple quantization backends, this approach reduces perplexity compared to standard baselines, particularly under low average bit-widths[cite: 1].

---

### Authors
Junchen Zhao, Ali Derakhshan, Jayden Hyman, **Junhao Dong**, Sangeetha Abdu Jyothi, Ian Harris[cite: 1]

---

### BibTeX
```bibtex
@inproceedings{zhao-etal-2026-coopq,
  title     = "{C}oop{Q}: Cooperative Game Inspired Layerwise Mixed Precision Quantization for {LLM}s",
  author    = "Zhao, Junchen and Derakhshan, Ali and Hyman, Jayden and Dong, Junhao and Abdu Jyothi, Sangeetha and Harris, Ian",
  booktitle = "Findings of the Association for Computational Linguistics: ACL 2026",
  month     = jul,
  year      = "2026",
  address   = "San Diego, California, United States",
  publisher = "Association for Computational Linguistics",
  pages     = "7566--7578",
  url       = "[https://aclanthology.org/2026.findings-acl.373/](https://aclanthology.org/2026.findings-acl.373/)",
  doi       = "10.18653/v1/2026.findings-acl.373"
}
