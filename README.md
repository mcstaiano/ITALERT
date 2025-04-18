**ITALERT** (Italian Emergency Response Text) is a novel bilingual corpus designed to investigate the performance of Large Language Models (LLMs) and Neural Machine Translation (NMT) systems in translating high-stakes emergency messages. The dataset is part of a broader effort to assess translation quality in critical contexts, using a human-centric post-editing based metric (HOPE) and inter-annotator agreement analysis.

The initial version of the ITALERT corpus contains 440 sentence-level segments extracted from the official website of the Italian Civil Protection Department, as part of the "Io non rischio" public communication campaign. 
The texts cover eight crisis scenarios: flooding, earthquake, forest fire, volcanic eruption, tsunami, industrial accident, nuclear risk, and dam failure.

The corpus currently comprises a total of **13,218 words** — 6,622 in Italian and 6,596 in English — and is distributed across the eight emergency subdomains. Each segment has been translated automatically by different systems (namely GPT-4o by OpenAI and Google Translate) and then annotated manually by three human annotators to assess translation quality.

The annotations capture:
- Binary error presence
- Fine-grained error types (accuracy, fluency, register, terminology, etc.)
- Inter-annotator agreement metrics (e.g., Fleiss' Kappa, Krippendorff's Alpha, Cohen's Kappa, IRR)

---
**Paper**:  
Staiano, M. C., Han, L., Monti, J., & Chiusaroli, F. (2025). ITALERT: Assessing the Quality of LLMs and NMT in Translating Italian Emergency Response Text. In Proceedings of the 20th Machine Translation Summit, Translator and Users Track. Geneva, Switzerland.
