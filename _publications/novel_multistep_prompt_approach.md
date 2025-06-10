---
title: "A Novel Multi-Step-Prompt Approach for LLM-based Q&As on Banking Supervisory Regulations"
collection: publications
category: manuscripts
permalink: /publication/multi-step-prompt
excerpt: 'The paper investigates the use of LLMs in Q&A related task in Banking sector. Done in collaboration with Bank of Italy. We use Retrieval Augmented Generation involving fine-tuning a reranker model with contrastive loss'
date: 2025-04-25
venue: 'Bank of Italy Occasional Paper'
paperurl: 'https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5252888'
citation: 'Daniele Licari, Canio Benedetto, Daniele Bovi, Praveen Bushipaka, Alessandro De Gregorio, Marco De Leonardis, Tommaso Cucinotta'
---

This paper investigates the use of large language models (LLMs) in analysing and answering questions related to banking supervisory regulations. We propose a multi-step-prompt approach that enriches the context provided to the LLM with relevant articles from the Capital Requirements Regulation (CRR). We compare our method against standard ‘zero-shot’ prompting, where the LLM answers are solely based on its pre-trained knowledge, and a standard ‘few-shot’ prompting, where the LLM is given only a limited number of examples of questions and answers to draw on each time. To assess the quality of the answers returned by the LLM, we also build an ‘LLM evaluator’ which, for each question, compares the correctness and completeness of the answer resulting from our multi-step prompt approach and from the two standard prompting methods with the official answer made available by the European Banking Authority (EBA), which is taken as a benchmark. Our findings on inquiries concerning Liquidity Risk rules indicate that our multi-step approach significantly improves the quality of LLM-generated answers, offering the analyst a valuable starting point to formulate appropriate answers to particularly complex questions. 

To cite the paper:
```
Licari, Daniele and Benedetto, Canio and Bovi, Daniele and Bushipaka, Praveen and De Gregorio, Alessandro and De Leonardis, Marco and Cucinotta, Tommaso, A Novel Multi-Step-Prompt Approach for LLM-based Q&As on Banking Supervisory Regulations (April 23, 2025). Bank of Italy Occasional Paper No. 935, Available at SSRN: https://ssrn.com/abstract=5252888 or http://dx.doi.org/10.2139/ssrn.5252888
```



