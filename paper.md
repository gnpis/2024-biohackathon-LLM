---
title: 'BioHackrXiv  template'
tags:
  - replace with your own keywords
  - at least 3 is recommended
authors:
  - name: First Last
    orcid: 0000-0000-0000-0000
    affiliation: 1
  - name: Second Last
    orcid: 0000-0000-0000-0000
    affiliation: 2

affiliations:
 - name: Institution 1, address, city, country
   index: 1
 - name: Institution 1, address, city, country
   index: 2
date: 01 January 2020
bibliography: paper.bib
authors_short: Last et al. (2021) BioHackrXiv  template
group: BioHackrXiv
event: BioHackathon Europe 2021
---

# Background

The aim of the project is lowering the barriers of interacting with integrated datasets represented in knowledge graphs based on data from biological, biomedical and agricultural sciences. We will create a bespoke knowledge graph (KG) by developing adapters based on Bioschemas markup and BreedingAPI (BrAPI) endpoints from diverse resources using BioCypher. Afterwards, we will connect the KG to current Large Language Model (LLM) technologies using BioChatter, which allows researchers to query the graphs in natural language. As many researchers are not semantic experts this will enable them to find interesting and integrated datasets without being familiar with knowledge graphs or query languages such as SPARQL or Cypher. One example use case is the integration of phenotypic data with plant genetic resources and pedigree information. To evaluate our approach we will benchmark a set of common questions and use cases provided by the diverse group of participants.  The project combines success stories from previous BioHackathon Germany, BioHackathon Europe and BioHackathon Japan work. A novelty is the extension of our generic user-friendly knowledge management infrastructure towards the agroscience domain. We will define several queries in natural language, to validate and benchmark our implementation and foster its robustness.

The emergence and rapidly increasing popularity of ChatGPT, CoPilot or Gemini have shown how powerful LLMs are. While we have made great progress in research data management and especially in the interoperability of research data in recent years, driven by the FAIR principles, the concrete interaction with this type of data is still a major hurdle for many scientists. The chatbot we are developing will provide the opportunity to combine these advances in data management with state-of-the-art technologies to provide the end user with a highly intuitive research platform that can be used without the need to read tutorials or attend workshops.


**Please separate paragraphs with a double line.**

## BrAPi use case

Please keep sections to a maximum of three levels, even better if only two levels.

### Objectives and sicentific questions

### Outcomes

### Future Work

### GitHub repositories and data repositories

* 

## Template use case

Please keep sections to a maximum of three levels, even better if only two levels.

### Objectives and sicentific questions

### Outcomes

### Future Work

### Jupyter notebooks, GitHub repositories and data repositories

* Please add a list here
* Make sure you let us know which of these correspond to Jupyter notebooks. Although not supported yet, we plan to add features for them
* And remember, software and data need a license for them to be used by others, no license means no clear rules so nobody could legally use a non-licensed research object, whatever that object is

## Tables, figures and so on

Please remember to introduce tables (see Table 1) before they appear on the document. We recommend to center tables, formulas and figure but not the corresponding captions. Feel free to modify the table style as it better suits to your data.

Table 1
| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

Remember to introduce figures (see Figure 1) before they appear on the document. 

![BioHackrXiv logo](./biohackrxiv.png)
 
Figure 1. A figure corresponding to the logo of our BioHackrXiv preprint.

# Other main section on your manuscript level 1

Feel free to use numbered lists or bullet points as you need.
* Item 1
* Item 2

# Discussion

Gathering biologists, bioinformaticians and AI experts has been a very efficient way to greatly increase our knowledge of the capabilities and limitation of Biochatter and Biocypher. We better undrestood what they can do with those technologies, how they can interact with existing knowledge graphs, with APIs or data file sources. We have seen that for isolated questions it works well against APIs, but when dealing with complex workflows such as chaining APIs call, programatic approaches are better suited. Indeed, Biochatter cannot easily infer this buisness logic without overspecyfying the ChatBot prompt, which is hardly sutainable or stable over time.

# Future work

There will be further implementation by the different groups in some of their tools and services. Thanks to this biohackathon, we will have the opportunity to further explore the solutions to answer the scientific questions we have listed.



# Acknowledgements
Please always remember to acknowledge the BioHackathon, CodeFest, VoCamp, Sprint or similar where this work was (partially) developed.

# References

Leave thise section blank, create a paper.bib with all your references.


For citations of references, we prefer the use of parenthesis, last name and year. If you use a citation manager, Elsevier – Harvard or American Psychological Association (APA) will work. If you are referencing web pages, software or so, please do so in the same way. Whenever possible, add authors and year. We have included a couple of citations along this document for you to get the idea. Please remember to always add DOI whenever available, if not possible, please provide alternative URLs. You will end up with an alphabetical order list by authors’ last name.
