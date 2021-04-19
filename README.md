# Demo: Knowledge Graph-Based Housing Market Analysis
The housing market is complex and multi-faceted, which makes its analysis challenging for users and professionals. We develop a four-step knowledge graph-based knowledge extraction approach for the housing market for efficient and accurate data analysis, consisting of data acquisition and cleaning, entity linking, ontology mapping, and question answering. The proposed system allows one to summarize the housing information for a selected geographical area, analyze the surroundings by collecting census data, understand the medical safety based on COVID-19 data, and the area attractiveness based on celebrities data from DBpedia. Our system can provide personalized recommendations given keywords and information about the market over time. A user-based evaluation demonstrates the utility of our system.

Arthur: Ziping Hu, Zepei Zhao, Mohammad Rostami, Filip Ilievski, Basel Shbita

Demo: https://www.youtube.com/watch?v=-2dZRv0YEQE&t=5s

Tools and language: Flask, Python, HTML, CSS, Neo4j

Data Source:

- apartments.com
- apartmentFinder.com
- DBpedia
- US Census
- Covid-19 dataset

Project Overview:

- Data Aquisition: Scrapy, SPARQL
- Data Cleaning: python
- Entity Linking: RLTK(similarity)
- Ontology Mapping: Neo4j, Cypher
- Web Development: Flask, Python, HTML, CSS
- Query Procession: Spacy, LDA
