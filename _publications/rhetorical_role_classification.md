---
title: "Automatic rhetorical roles classification for legal documents using legal-transformer-over-bert"
collection: publications
category: conferences
permalink: /publication/Rhetorical-role-classification
excerpt: 'In this paper we present a novel rhetorical role classification technique. The paper was accepted to 6th workshop on Automated semantic analysis of information in legal text.'
date: 2023-09-23
venue: 'ASAIL-23'
paperurl: '[https://dl.acm.org/doi/abs/10.1145/3594536.3595177)](https://ceur-ws.org/Vol-3441/paper4.pdf)'
citation: 'Gabriele Marino, Daniele Licari, Praveen Bushipaka, Giovanni Comandé, Tommaso Cucinotta'
---

Automatic identification of rhetorical roles can help in many downstream applications of legal documents analysis, such as legal decisions summarization and legal search. This is usually a complex task, even for humans, due to its inherent subjectivity and to the difficulty of capturing sentence context in very long legal documents. We propose a novel approach, based on Hierarchical Transformers, which overcomes these problems and achieves promising results on two different datasets of Italian and English legal judgments. Specifically, we introduce LEGAL-TransformerOverBERT (LEGAL-ToBERT), a model based on the stacking of a transformer encoder over a legal-domain-specific BERT model, and show that our approach is able to significantly improve the baselines set by the stand-alone LEGAL-BERT models, by capturing the relationships between different sentences of the same document. We make our models available and ready-to-use for downstream applications of rhetorical roles classification in the legal context both for the Italian and English language.

To cite the paper:
```
@inproceedings{10.1145/3594536.3595177,
author = {Licari, Daniele and Bushipaka, Praveen and Marino, Gabriele and Comand\'{e}, Giovanni and Cucinotta, Tommaso},
title = {Legal Holding Extraction from Italian Case Documents using Italian-LEGAL-BERT Text Summarization},
year = {2023},
isbn = {9798400701979},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3594536.3595177},
doi = {10.1145/3594536.3595177},
abstract = {Legal holdings are used in Italy as a critical component of the legal system, serving to establish legal precedents, provide guidance for future legal decisions, and ensure consistency and predictability in the interpretation and application of the law. They are written by domain experts who describe in a clear and concise manner the principle of law applied in the judgments.We introduce a legal holding extraction method based on Italian-LEGAL-BERT to automatically extract legal holdings from Italian cases. In addition, we present ITA-CaseHold, a benchmark dataset for Italian legal summarization. We conducted several experiments using this dataset, as a valuable baseline for future research on this topic.},
booktitle = {Proceedings of the Nineteenth International Conference on Artificial Intelligence and Law},
pages = {148–156},
numpages = {9},
keywords = {Benchmark Dataset, Extractive Text Summarization, Holding Extraction, Italian-LEGAL-BERT},
location = {Braga, Portugal},
series = {ICAIL '23}
}
```



