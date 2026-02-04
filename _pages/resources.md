---
permalink: /resources/
title: "Project Resources"
author_profile: true
---

## Data
The resources used in Mormor Karl project ('Grandma Karl' in English) consist of several datasets, some of which are under development. Since most of them contain personal information, most of the datasets are not openly avaiable. We will - after thorough legal and ethical considerations - create open datasets that could be used for benchmarking.

------

### Primary data -- SweLL corpus

[SweLL](https://spraakbanken.gu.se/en/projects/swell/swell4users) (Swedish Language Learner) corpus contains a collection of ≈1000 digitized essays written by second language learners of Swedish at different levels of proficiency. SweLL essays have rich metadata information about the writers, text types and topics, and contain multiple samples of use of personal information in a variety of topical domains. All personal mentions have been manually labeled for their types to make it possible to work on the development  automatic pseudonymization tools.

* SweLL-gold corpus, 502 essays: see corpus [metadata](https://spraakbanken.github.io/swell-release-v1/Metadata-SweLL) and [article](https://nejlt.ep.liu.se/article/view/1374) 
* SweLL-pilot corpus, 502 essays, consists of three subcorpora, as described in the [article](http://arxiv.org/pdf/1604.06583v1.pdf):
    - SpIn: see  [SpIn metadata](https://spraakbanken.github.io/swell-release-v1/Metadata-SpIn)
    - SW1203: see [SW1203 metadata](https://spraakbanken.github.io/swell-release-v1/Metadata-SW1203)
    - TISUS: see [TISUS metadata](https://spraakbanken.github.io/swell-release-v1/Metadata-TISUS) 

------

### Texts with fictive personal information

We are conducting a collection of texts (legal texts and personal stories) written by real people about fictive characters.


### Data from other domains (in Swedish)

* Medical data 
* News data <!-- Hercules -->
* Social media data
* Working stories <!-- Leif-Jöran -->

<!--## Data in other languages -->

------

## Tools

We start from the [SVALA tool](https://spraakbanken.gu.se/swell/dev/), where rule-based automatic pseudonymizer service is available in the menu for tesing, see an [article on SVALA](http://www.ep.liu.se/ecp/159/023/ecp18159023.pdf).

We have developed a [SPARV plugin](https://spraakbanken.gu.se/analyser/sbx-swe-pi_detection-sparv) for personal information detection and labelling. 

The models available in that plugin are available on [HuggingFace](https://huggingface.co/collections/Turtilla/pi-detection-and-labeling).

We have collaborated with InfraVis to develop a [visualization tool](https://github.com/spraakbanken/impersonaldata) for comparing personal information detection and labeling from different systems. 

As more tools and algorithms will be developed in the project, they will appear here. 

------

<!-- We have released several datasets, tools, and documents as part Mormor Karl project. Here you can find them:-->

<!--
- [Datasets](./datasets/)
- [Tools and Software](./tools/)
- [Documentation and Reports](./reports/)
-->
