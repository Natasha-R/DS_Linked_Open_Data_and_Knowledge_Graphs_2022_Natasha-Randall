# Linked Open Data & Knowledge Graphs: Digital Sciences WS2022 Final Project

This repository contains the final project of the course 
["Linked Open Data and Knowledge Graphs"](https://digital-sciences.de/en/modules/linked-open-data-and-knowledge-graphs/) for the Digital Sciences Master's Degree at TH Köln.

## Project Description

The goal of this project was to compare disease-symptom association health knowledge graphs created from three disparate data sources, and to explore the viability of combining the datasets into one large encompassing health knowledge graph.

This project was inspired by the paper: Rotmensch et al., 2017. Learning a health knowledge graph from electronic medical records. Scientific reports, 7(1), 1-11. [A presentation of this paper](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/'Learning%20a%20Health%20Knowledge%20Graph'%20Presentation.md) is also provided.

The three datasets are:
1. Disease-symptom co-ocurrences in medical journal papers from PubMed. *Associated paper: Zhou, X., Menche, J., Barabási, AL. et al. Human symptoms–disease network. Nat Commun 5, 4212 (2014). https://doi.org/10.1038/ncomms5212.* Creative Commons Attribution 4.0 International license.
2. Disease entities and their dbo:symptom property in DBPedia.  (https://www.dbpedia.org/). Creative Commons Attribution-ShareAlike 3.0 License.
3. Patient disease diagnosis and symptom reports at a New York Hospital. *Associated paper: Wang X, Chused A, Elhadad N, Friedman C, Markatou M. Automated knowledge acquisition from clinical narrative reports. AMIA Annu Symp Proc. 2008 Nov 6;2008:783-7.* Open Access: verbatim copying and redistribution are permitted in all media for any purpose.

## Project Contents

The main code for the project is contained within Jupyter notebooks, released under the MIT licence.   

Importing, processing and fixing the three datasets:   
[1. DBPedia Dataset](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/1.%20DBPedia%20Dataset.ipynb)  
[2. PubMed Dataset](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/2.%20PubMed%20Dataset.ipynb)  
[3. Medical Records Dataset](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/3.%20Medical%20Records%20Dataset.ipynb)  

A supplemental exploration of methods to fix missing MeSH codes and an approach to represent conditions by their "parent category":  
[4. Example Methods to Fix Discrepancies](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha_Randall/blob/main/4.%20Example%20Methods%20to%20Fix%20Discrepancies.ipynb)  

Comparing the three datasets and combining them:   
[5. Combining Datasets](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/5.%20Combining%20Datasets.ipynb)  
[6. Comparing the Health Knowledge Graphs](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha-Randall/blob/main/6.%20Comparing%20the%20Health%20Knowledge%20Graphs.ipynb)

Network visualisations and calculating graph metrics in Gephi:
[7. Work in Gephi](https://github.com/Natasha-R/DS_Linked_Open_Data_and_Knowledge_Graphs_2022_Natasha_Randall/tree/main/gephi_analysis)

The data are all contained in the relevant folders.
