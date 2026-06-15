---
layout: default
title: Home
---

## INTRODUCTION

The project was carried out within the framework of the Knowledge Engineering for the Humanities course at the [University of Bologna](https://www.unibo.it/en). The objective was to combine **SPARQL queries** and **Large Language Models (LLMs)** to enrich an existing cultural heritage knowledge graph with new information. By integrating structured knowledge extraction with AI-generated insights, the project explores the potential of these technologies to enhance the representation and accessibility of cultural heritage data.

We chose the [Spedale del Ceppo](https://en.wikipedia.org/wiki/Ospedale_del_Ceppo) in [Pistoia](https://en.wikipedia.org/wiki/Pistoia) as our topic, one of the most significant hospital complexes in [Tuscany](https://en.wikipedia.org/wiki/Tuscany). The building, a historic 13th-century hospital, represents an important example of architectural, artistic, and social heritage, reflecting centuries of healthcare practices and urban development. The Spedale del Ceppo is a cornerstone of Pistoia's civic identity. Having served as the city's primary hospital for over seven centuries, it represents the historical heart of local social welfare and remains a focal point of the urban landscape. Today, the former hospital operates as a museum and serves as the gateway to the city's underground archaeological pathways (*[Pistoia Sotterranea](https://www.pistoiasotterranea.it/)*). Its rich historical background, as well as the presence of notable artistic elements, makes it a particularly interesting case of study for cultural heritage research.

Furthermore, the limited representation of the Spedale del Ceppo within existing knowledge graphs provided an opportunity to investigate how semantic technologies and Large Language Models can contribute to the enrichment of cultural heritage data.

We used [ArCo](http://wit.istc.cnr.it/arco), the official ontology network and RDF dataset of the Italian Ministry of Culture, as our foundational knowledge graph. ArCo delivers a comprehensive representation of Italy's cultural heritage and features a robust SPARQL endpoint for deep semantic querying. Furthermore, its modular design and domain-specific ontologies perfectly align with our project goals, particularly regarding tangible cultural assets.

## TOOLS:

1. [ArCo](http://wit.istc.cnr.it/arco/)
2. [ArCo SPARQL endpoint](https://dati.cultura.gov.it/sparql)
3. [ChatGPT](https://chatgpt.com/)
4. [Gemini](https://gemini.google.com/app)

## LET'S MEET THE GROUP:

This project was collaboratively developed by:

**[Alice Lorenzi](https://github.com/alice-lorenzi)**

![Alice Lorenzi](images/alice-lorenzi.png)

**[Chiara Middei](https://github.com/Chiaramiddei)**

![Chiara Middei](images/chiara-middei.jpg)

**[Camilla Vinotti](https://github.com/camylla02)**

![Camilla Vinotti](images/camilla-vinotti.jpg)

**[Anna Laura Ricciardi](https://github.com/annalauraricci)**

![Anna Laura Ricciardi](images/annalaura-ricciardi.jpg)

---

# SPEDALE DEL CEPPO

## A masterpiece of the medieval architecture in Pistoia

**Overview of the structure:**

![Overview of the structure](images/overview-struttura.png)

**Frieze and medallions:**

![Frieze and medallions](images/fregio-medaglioni.png)

**Teatrino Anatomico**

![Teatrino Anatomico](images/teatrino-anatomico.png)

**Pistoia Sotterranea**

![Pistoia Sotterranea](images/pistoia-sotterranea.png)

Founded in **1277**, the **Spedale del Ceppo in Pistoia** stands as a monumental testament to both medical history and Renaissance art. Having functioned continuously as the city's primary healthcare institution for over seven centuries, most notably during the [Black Death](https://en.wikipedia.org/wiki/Black_Death) of 1348, the complex expanded organically over time. Its vast architectural structure is unified by a magnificent 16th-century loggia, inspired by Brunelleschi's Florentine models. The loggia's façade is crowned by a spectacular polychrome glazed terracotta frieze crafted by [Santi Buglioni](https://en.wikipedia.org/wiki/Santi_Buglioni), vividly illustrating the Seven Works of Mercy interspersed with the Virtues, and is beautifully complemented by exquisite medallions (**tondi**) by [Giovanni della Robbia](https://en.wikipedia.org/wiki/Giovanni_della_Robbia).

Beyond its artistic exterior, the Spedale was a prominent center for scientific advancement, home to a prestigious [Medical Academy](https://www.accademiafilippopacini.it/). Inside, it preserves a rare 18th-century Anatomical Theatre ([Teatrino Anatomico](https://blogcamminarenellastoria.wordpress.com/2021/04/27/il-teatro-anatomico-della-scuola-medica-di-pistoia/)), a small, elegantly frescoed amphitheater historically used for dissections and medical instruction. Today, the complex operates as a museum and serves as the gateway to Pistoia Sotterranea, a fascinating underground archaeological pathway that winds beneath the hospital through ancient, vaulted riverbeds, revealing centuries of layered urban and architectural history.

We thought that the **Spedale del Ceppo matches perfectly with this project** because:

1. This iconic **Tuscan** site holds immense historical value and is closely tied to the local heritage and cultural identity of Pistoia.
2. **The site blends art, medicine, and archaeology,** providing a rich basis for creating semantic connections with similarly complex historical monuments.
3. Even though current records are factually sound, **we can greatly enrich its structural representation by adding missing details and broader semantic relations.**
4. The Spedale is situated in the hometown of one of our team members, Chiara, while Alice visited it during a school trip in elementary school.

## PROJECT GOALS

1. To query the **ArCo ontology** network via its dedicated SPARQL endpoint, aiming to retrieve pertinent and structured data concerning the subject of our project: Spedale del Ceppo.
2. To employ advanced **Large Language Models** (e.g., ChatGPT and Gemini) to generate novel insights and formulate new RDF triples, that could enrich the ArCo Knowledge Graph.
