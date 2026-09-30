---
title: "Preserving the Privacy of Language Data: Emerging Technologies, Evolving Standards and Beyond"
excerpt_separator: "<!--more-->"
categories:
  - events
tags:
  - outreach
  - blog
---

## A special issue @ [Language Resources and Evaluation](https://link.springer.com/journal/10579) Journal 

| Quick links |
|--|
|- [Guest editors and contact information](#guest-editors-and-contact-information) <br> - [Call for submissions](#call-for-submissions) <br> - [Important dates](#important-dates) <br> - [Submission information](#submission-information) <br> - [AI disclosure statement](#ai-disclosure-statement) <br> - [References](#references)

## Guest editors and contact information

- [Elena Volodina](https://spraakbanken.gu.se/en/about/staff/elena), University of Gothenburg, Sweden, `<` elena dot volodina at svenska dot gu dot se `>`
- [Maria Irena Szawerna](https://spraakbanken.gu.se/en/about/staff/maria-szawerna), University of Gothenburg, Sweden, `<` maria dot szawerna at gu dot se `>`

## Call for submissions 

In the age of GDPR and heightened awareness about data privacy, incorporating de-identification techniques when working with language data has become increasingly important. In academic contexts, de-identification is employed e.g. when using examples in publications (Heaton, 2022; Wang et al., 2024) or in dataset collection and sharing (Megyesi et al., 2018; Eder et al., 2019). It is also relevant for public uses, such as redacting legal documents (Cabrera-Diego and Gheewala, 2024) or varied industry applications (Gardiner et al., 2024; Hou et al., 2025). Manual de-identification is a costly and time-consuming process, which is why various automatic methods for detecting and replacing personal information, ranging from rule-based systems to Large Language Model (LLM) approaches, have been developed in recent years (Deußer et al., 2025). While rule-based approaches allow for processing the data locally, reducing the risk of the data falling into the wrong hands, they lack the ability to take semantic context and world knowledge into account; LLMs, on the other hand, can handle these challenges to a certain degree, but present ethical concerns when it comes to data leakage, environmental costs, or over-relying on encoded social and gender biases (Bender et al., 2021; Volodina et al. 2025, Szawerna and Suchardt, 2026). <br> This special issue will cover several aspects related to the problem of using technology for effective and ethical de-identification of linguistic data, including (but not limited to) the following topics:<br>
- **Detection and classification of personal information (PI)**: Automatic identification of PI in text, speech, and multimodal data; context-dependent and indirect indicators of identity. Which information you are replacing, including how and why this is done.
- **Replacement and transformation of PI**: Context-sensitive pseudonymization and anonymization methods; substitution, masking, obfuscation; maintaining coherence across discourse and modalities.
- **Utility and bias after de-identification**: Effects of de-identification on downstream task performance, linguistic research validity, readability, and bias amplification or reduction. 
- **Approaches to evaluation and adversarial testing**: Metrics and frameworks for assessing de-identification quality; adversarial re-identification attempts; robustness and failure-mode analysis.
- **Dataset creation for de-identification research**: Methodological, ethical, and annotation-related considerations in building corpora for training or evaluating de-identification systems.
- **Low-resource scenarios**: Techniques for de-identification in settings with limited data, scarce annotations, or underrepresented languages; transfer and multilingual approaches.
- **Speech-specific challenges**: Removing speaker identity cues in audio; voice anonymization; cross-modal leakage between text, transcripts, and acoustic features.
- **Cross-disciplinary applications and challenges**: Integrating de-identification techniques into real-world workflows in areas such as linguistics, social sciences, digital humanities, healthcare, and other private- or public-sector data environments. <br><br>

## Important dates

- October, 1, 2026: 1st call submissions 
- November, 2, 2026: Expressions of interest due
- November, 30, 2026: Notifications of abstract acceptance and invitation for full paper submission
- March, 1, 2027: Full paper submissions due 
- August 2027: Notification of full paper acceptance 
- December 2027: Final manuscripts submitted 

## Submission information

- **Abstracts** should be around 500 words excluding references and statements. The submission link can be found [here](https://forms.cloud.microsoft/e/gBuU6Wih9Z). Authors of accepted abstracts will be notified by the end of November, and invited to submit a full article by 1st March 2027. 
- **Full Articles** should follow the [LRE journal guidelines](https://link.springer.com/journal/10579/submission-guidelines). Each submission should include an [AI disclosure statement](ai-disclosure-statement). The submission link will be shared later.


## AI disclosure statement

Please, include in your submission (alongside the abstract) the following table/list, based on [Kamocki and Witt (2026)](https://aclanthology.org/2026.legal-1.pdf#page=47). For each use category in the table (except the first and the last ones), please indicate "yes" or "no". For "Generation from prompt", provide more details. Note that articles generated from prompt and polished afterwards cannot legally be assigned authorship to humans and will therefore be excluded from reviewing and publication in the special issue. 

Read more about policy regarding the use of AI for article writing (and other related policies) at the [Springer Nature Link](https://link.springer.com/brands/springer/journal-policies) website.


| AI use category | Explanation | 
|--|--|
| AI tool | Name and version  | 
| Assistive use | Idea generation, topic discovery, argument development and critique, gap identification, summarising and suggesting sources|
| Editing | Grammar and syntax correction, spellchecking, flow improvement, style and tone adaptation |
| Generation of minor elements | Generation of introduction/conclusion/abstract, finding examples (including e.g. linguistic structures)|
| Translation | Translation of the entire manuscript, translation of source texts/quotations |
| Compression/expansion | Using AI to shorten or expand existing human-generated input to meet word/page limit |
| Generation from prompt | Generation of an entire article from a prompt with a human assuming editorial control over the output |


## References 
- Emily M. Bender, Timnit Gebru, Angelina McMillan-Major, and Shmargaret Shmitchell. 2021. On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜. In Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (FAccT '21). Association for Computing Machinery, New York, NY, USA, 610–623. <br>
- Luis Adrián Cabrera-Diego and Akshita Gheewala. 2024. PSILENCE: A pseudonymization tool for international law. In Proceedings of the Workshop on Computational Approaches to Language Data Pseudonymization (CALD-pseudo 2024), pages 25–36, St. Julian’s, Malta. Association for Computational Linguistics.<br>
- Tobias Deußer, Lorenz Sparrenberg, Armin Berger, Max Hahnbück, Christian Bauckhage, and Rafet Sifa. 2025. A survey on current trends and recent advances in text anonymization. In 2025 IEEE 12th International Conference on Data Science and Advanced Analytics (DSAA), pages 1–9.<br>
- Elisabeth Eder, Ulrike Krieg-Holz, and Udo Hahn. 2019. De-identification of emails: Pseudonymizing privacy-sensitive data in a German email corpus. In Proceedings of the International Conference on Recent
Advances in Natural Language Processing (RANLP 2019), pages 259–269, Varna, Bulgaria. INCOMA Ltd.<br>
- Shayna Gardiner, Tania Habib, Kevin Humphreys, Masha Azizi, Frederic Mailhot, Anne Paling, Preston
Thomas, and Nathan Zhang. 2024. Data anonymization for privacy-preserving large language model fine-tuning on call transcripts. In Proceedings of the Workshop on Computational Approaches to Language
Data Pseudonymization (CALD-pseudo 2024), pages 64–75, St. Julian’s, Malta. Association for Computational Linguistics.<br>
- Janet Heaton. 2022. “* pseudonyms are used throughout”: A footnote, unpacked. Qualitative Inquiry, 28(1):123–132.<br>
- Shilong Hou, Ruilin Shang, Zi Long, Xianghua Fu, and Yin Chen. 2025. A general pseudonymization framework for cloud-based LLMs: Replacing privacy information in controlled text generation. Preprint, arXiv:2502.15233.<br>
- Paweł Kamocki and Andreas Witt. 2026. Authorship Attribution in the Times of LLMs within the Framework of the CRediT Taxonomy. In Joint Workshop
on Legal and Ethical Issues in Human Language Technologies and Computational Approaches to Language Data Pseudonymization, Anonymization, De-identification, and Data Privacy (LEGAL2026 and CALD-pseudo 2026)@ LREC 2026 (p. 35).<br>
- Beáta Megyesi, Lena Granstedt, Sofia Johansson, Julia Prentice, Dan Rosén, Carl-Johan Schenström, Gunlög Sundberg, Mats Wirén, and Elena Volodina. 2018. Learner Corpus Anonymization in the Age of GDPR: Insights from the Creation of a Learner Corpus of Swedish. In Proceedings of the 7th NLP4CALL, Swedish Language Technology Conference, SLTC 2018, pages 47–56.<br>
- Maria Irena Szawerna and Jacob Lee Suchardt. 2026. Fill-in-the-Blanks: Automatic Generation and Evaluation of Language Models' Pseudonyms for English and Swedish Texts. In Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026), European Language Resources Association (ELRA), pages 1155–1169.<br>
- Elena Volodina, Simon Dobnik, Therese Lindström Tiedemann, Ricardo Muñoz Sánchez, Maria Irena Szawerna, Lisa Södergård, Xuan-Son Vu. 2025. Towards shared standards for pseudonymization of research data. In Proceedings of the Huminfra Conference (HiC 2025), Stockholm, 12-13 November 2025.<br>
- Sixuan Wang, Junjun Muhamad Ramdani, Shuting Sun, Priyanka Bose, and Xuesong Gao. 2024. Naming research participants in qualitative language learning research: Numbers, pseudonyms, or real names? Journal of language, identity & education, pages 1–14.
