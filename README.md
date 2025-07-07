
# Melbourne Housing Crisis — NLP & Network Analysis

> Natural-language & network exploration of News articles, Policy documents and Reddit threads on the 2025 Melbourne housing crisis.


## 📑 Project at a Glance
| &nbsp; | Highlights |
|-------|------------|
| **Corpus** | 20 public-domain documents across three genres (NEWS 8 📰, POLICY 5 📜, REDDIT 7 💬) |
| **Methods** | · `tm`, `SnowballC` for preprocessing<br>· Harvard GI lexicon for sentiment<br>· Cosine-distance clustering (`proxy`, `hclust`)<br>· Token/document networks (`igraph`)<br>· Bipartite projection & centrality metrics |
| **Findings** | • **Policy docs** are most optimistic (SentimentGI ↑)<br>• **Reddit** acts as a lexical bridge between news & policy<br>• 26 high-frequency tokens (‘hous’, ‘afford’, ‘home’, …) dominate all genres |
| **Takeaway** | Despite different voices, every stakeholder repeats the same vocabulary—evidence that new ideas, not new words, are needed to solve the crisis. |


Reflection
“Every dataset tells a story; this one told mine.”
Building the corpus from scratch (scraping ABC articles, clipping policy PDFs, exporting Reddit threads) taught me that data wrangling is 80 % of analysis. Watching “forever-renters” top every centrality ranking was equal parts validation and frustration—it mirrored my own struggle to crack Melbourne’s market.

This report earned credit for FIT3152 (2025).
It is published for portfolio purposes only.
Current students must not submit any part of this work as their own; Monash University regards that as plagiarism.
