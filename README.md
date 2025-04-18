**ITALERT** is a novel bilingual corpus designed to investigate the performance of Large Language Models (LLMs) and Neural Machine Translation (NMT) systems in translating high-stakes emergency messages. The dataset is part of a broader effort to assess translation quality in critical contexts, using a human-centric post-editing based metric (HOPE) and inter-annotator agreement analyses.

The initial version of the ITALERT corpus contains 440 sentence-level segments extracted from the official website of the Italian Civil Protection Department, as part of the "Io non rischio" public communication campaign. The texts cover eight crisis scenarios: flooding, earthquake, forest fire, volcanic eruption, tsunami, industrial accident, nuclear risk, and dam failure. The corresponding English translations were sourced from the same institutional website.

The corpus currently comprises a total of **13,218 words** — 6,622 in Italian and 6,596 in English — and is distributed across the eight emergency subdomains. Each segment has been translated automatically by different systems (including GPT-4o by OpenAI and Google Translate) and then annotated manually by multiple human annotators to assess translation quality.

The annotations capture:
- Binary error presence
- Fine-grained error types (accuracy, fluency, register, terminology, etc.)
- Inter-annotator agreement metrics (e.g., Fleiss' Kappa, Krippendorff's Alpha)

**Findings from our pilot evaluation show that current LLMs and NMT systems exhibit notable limitations**, especially in terms of register consistency, context disambiguation, and management of domain-specific terminology in emergency-related content.

The dataset has been carefully compiled to ensure clarity and usability for evaluating MT systems in real-world crisis communication scenarios.

> The corpus and all evaluation files are hosted openly on GitHub:  
> 🔗 [https://github.com/mcstaiano/ITALERT](https://github.com/mcstaiano/ITALERT)

---

**Paper**: *ITALERT: Assessing the Quality of LLMs and NMT in Translating Italian Emergency Response Text*  
Maria Carmen Staiano, Lifeng Han, Johanna Monti, and Francesca Chiusaroli.  
In *20th Machine Translation Summit: Products and Projects track*, Geneva, Switzerland.  
European Association for Machine Translation.
