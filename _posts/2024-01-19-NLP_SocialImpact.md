---
layout: single
title:  "NLP for Social Good: Insights from Gun Violence Dataset"
permalink: /NLP_SocialImpact/

---

In our recent study with Upasana Dutta, Hita Kambhamettu, and Neil Sehgal, we harnessed NLP to tackle gun violence data extraction from news articles. This collaborative effort underscores large language models' potential for annotating large datasets with little human input. Our study builds upon the [Gun Violence Database](https://aclanthology.org/D16-1106/), a crucial resource for NLP as detailed in the work by Ellie Pavlick, Heng Ji, Xiaoman Pan, and Chris Callison-Burch ([Pavlick et al., EMNLP 2016](https://aclanthology.org/D16-1106/)).

Key achievements include fine-tuning a relatively tiny Flan-T5 model, which improved its approximate F1 score in annotating key points in the text from 36% to 67%. Exploring GPT models, we found that GPT 3.5 Zero-Shot achieved a 66% approximate F1 score, and GPT-4 with Three-Shot prompting reached 76%. These results highlight how different prompting strategies influence the efficacy of advanced LLMs in complex information extraction.

I had the privilege of sharing these insights at the Semantica Lab's meeting at the [Institute for Biomedical Informatics](https://ibi.med.upenn.edu/), led by [Danielle L. Mowery](https://www.med.upenn.edu/apps/faculty/index.php/g275/p9165197), fostering discussions on using LLMs in annotating unstructured text in health contexts (e.g., EHR data or provider-patient interactions).

