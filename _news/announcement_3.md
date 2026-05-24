---
layout: post
title: "My sole author publication at <a href='https://nips2025fm4ls.github.io/pages/organizers.html'> NeurIPS'25 FM4LS </a> on <a href='https://arxiv.org/abs/2510.03309'>Drug-Text Alignment</a>. Please read my paper and let's meet at NeurIPS'25"
date: Tuesday, Sep 23, 2025, 12:50 AM
inline: false
related_posts: false
---

Here is my paper **Thin Bridges for Drug Text Alignment: Lightweight Contrastive Learning for Target Specific Drug Retrieval** abstract

---

Multimodal foundation models hold promise for drug discovery and biomedical applications, but most existing approaches rely on heavy pretraining or large scale multimodal corpora. We investigate whether thin contrastive bridges, lightweight projection heads over frozen unimodal encoders can align chemical and textual representations without training a full multimodal model. Using paired mechanisms from ChEMBL, we align ECFP4 molecular fingerprints with biomedical sentence embeddings through dual linear projections trained with a contrastive objective. To better handle drugs sharing the same therapeutic target, we incorporate hard negative weighting and a margin loss. Evaluation under scaffold based splits, which require generalization across disjoint chemical cores, demonstrates that our approach achieves non-trivial cross modal alignment and substantially improves within target discrimination compared to frozen baselines. These results suggest that thin bridges offer a compute efficient alternative to large scale multimodal pretraining, enabling scaffold aware drug text alignment and target specific retrieval in precision medicine.
