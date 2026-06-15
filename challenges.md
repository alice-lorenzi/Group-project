---
layout: default
title: Key Challenges
---

### Sections:

- [🏠 Home](index.html)
- [🏛️ Topic](topic.html)
- [⚒️ Semantic Methodology](methodology.html)
- [📈 SPARQL Queries & Data Results](sparql.html)
- [🧩 Gap Identification](gaps.html)
- [🤖 LLM Prompt: ChatGPT & Gemini](prompts.html)
- [🔗 RDF Triple Generation](rdf.html)
- [⚠️ Key Challenges](challenges.html)
- [🎯 Conclusions & Insights](conclusions.html)

<h1 style="color:#ff0000;">⚠️ Key Challenges</h1>

<h2 style="color:#ff0000;">CHALLENGES AND CONSIDERATIONS</h2>

![Challenges and Considerations](assets/images/challenges-considerations.png)

## Challenges Faced During the Project

- Our investigation focused on the **Spedale del Ceppo** ([https://w3id.org/arco/resource/Site/4215fe83165269413c37c21663c3d94b](https://w3id.org/arco/resource/Site/4215fe83165269413c37c21663c3d94b)), a historical building whose **knowledge graph is relatively limited** compared to other cultural heritage entities.
- When searching for the Spedale del Ceppo in [ArCo](http://wit.istc.cnr.it/arco/), the results primarily referred to the coat of arms (stemmi) rather than to the hospital itself. Consequently, **the search did not directly provide information about the cultural site** but instead returned a list of related elements associated with the emblem and medallions.
- The exploration process was constrained by the **limited number of available predicates and relationships**, making it difficult to identify relevant information and connections.
- One of the **main challenges** was **identifying information gaps concerning the hospital itself**. Since searching for the hospital mainly returned information about its emblem, we had to explore multiple related entities to retrieve data about the hospital as a cultural site. This required distinguishing between the emblem as a heritage object and the hospital as the primary subject of our investigation.
- **We identified four significant gaps**: **two related to the hospital and two related to the coat of arm**. To support this analysis, we compared the Spedale del Ceppo with other historical hospitals represented in [ArCo](http://wit.istc.cnr.it/arco/), such as the [Ex Ospedale della SS.ma Trinità in Bologna](https://w3id.org/arco/resource/ArchitecturalOrLandscapeHeritage/0800242653), the [Ex Ospedale della Misericordia in Grosseto](https://w3id.org/arco/resource/ArchitecturalOrLandscapeHeritage/0900352753A), the [Spedale degli Innocenti](https://w3id.org/arco/resource/Site/db159e90f5ed83e3d851e7206ccbbd2) in Florence... This comparison helped us understand which types of information are typically associated with hospitals and former hospitals in the knowledge graph.
- **Identifying both existing information and missing information proved challenging because of the complexity and interconnected nature of the data network.**
- During the interaction with artificial intelligence systems, **we often had to explicitly encourage step-by-step reasoning through Chain-of-Thought prompting technique**. **Without this guidance, the generated analyses tended to be superficial and incomplete**.

## Major Challenges in Gap Identification

- The first challenge concerned the hospital itself. Since the **hospital is only indirectly represented through its associated heritage objects**, identifying relevant information required extensive exploration of connected entities and properties. The first gap concerned whether **the hospital had undergone restoration interventions**, while the second concerned its **current function**. Although the Spedale del Ceppo currently operates as a **museum**, this **information was not explicitly represented in the knowledge graph**.
- The second challenge concerned the main coat of arm. Through comparison with similar hospitals (Spedale degli Innocenti in Florence), we observed that emblem-related information was commonly available. However, **our emblem lacked information regarding its shape and its commission**. Building the corresponding queries required careful identification of the appropriate predicates, particularly to avoid confusion between *hasCommission* and *hasCommittent*. **Further analysis revealed that the information we needed was not the commissioning event itself, but rather the agent responsible for commissioning the artwork.**

## Challenges in the use of ArCo, Query Construction and AI Evaluation

- We encountered **several difficulties when using artificial intelligence systems to generate SPARQL CONSTRUCT queries** for adding the missing information. To validate the generated outputs, we compared the performance of different AI models. [**ChatGPT**](https://chatgpt.com/) demonstrated a stronger capacity for in-depth analysis and was ultimately **more effective** in **producing correct and executable SPARQL CONSTRUCT queries**. In contrast, **Gemini** often **required additional modifications and refinements before generating a working query**, even when provided with the same prompt.
- We also had to deal with problems related to the functioning of the ArCo server/database, which resulted in a **delay in advancing with our project during some days**.
