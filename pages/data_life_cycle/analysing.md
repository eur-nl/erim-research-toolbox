---
title: Analysing
# related_pages:
#   your_tasks: [data_analysis, data_organisation, storage, data_provenance]
contributors: [Dr. Nami Sunami, Dr. Lizette Guzman-Ramirez]
description: Introduction to data analysis.
# training:
#   - name: Training in TeSS
#     registry: TeSS
#     url: https://tess.elixir-europe.org/search?q=%22data+analysis%22#materials
---

## What is data analysis?

Data analysis consists in exploring the collected data to begin understanding the messages contained in a dataset and/or in applying mathematical formula (or models) to identify relationships between variables.
The steps of the workflow in the analysis phase will often be repeated several times to explore the data as well as to optimize the workflow itself.
According to the different types of data (quantitative or qualitative) the data analysis methods will differ. Data analysis follows the (often automated, batch) data processing stage.

<!-- ERIM specific info (begin)-->

## What options do I have for analysing data as an ERIM member? 

ERIM has several options for its researchers to help analysing data data: 

- If you need IT Research Support, ERIM memebers can contact the [Research Software Engeneering & Consulting (RSEC) group <sup><i class="fa-solid fa-lock"></i></sup>](https://my.eur.nl/en/rsm-employee/services-0/rsm-digitalisation-and-information-services-rdis/rdis-rsm-eur/it-research-support)
- A list of all the software EUR employees have access can be found here: [EUR licensed tools <sup><i class="fa-solid fa-lock"></i></sup>](https://my.eur.nl/en/eur-employee/work-support/it/software/clientsoftware-center-application-request)
- [Data Processing Software](https://eur.nl/en/research/research-services/research-data-management/data-processing-software)
- [Anonymisation/Pseudonomisation tools](https://eur.nl/en/research/research-services/research-data-management/anonymisation-research-data)
- [Meta-Essentials](https://www.erim.eur.nl/research-support/meta-essentials/)
- In case the software you need is not avaible, as an ERIM member, you can apply for funding via the [ERIM Support Programs (ESP)](https://www.erim.eur.nl/research-support/erim-support-programmes-esp/)


<!-- ERIM specific info (end) -->

## Why is data analysis important?

Since data analysis is the stage where new knowledge and information are generated, it can be considered as central in the research process. Because of the relevance of the data analysis stage in research findings, it is essential that the analysis workflow applied to a dataset complies with the FAIR principles. Moreover, it is extremely important that the analysis workflow is reproducible by other researchers and scientists.  
With many disciplines becoming data-oriented, more data intensive projects will arise which will require experts from dedicated fields.

## What should be considered for data analysis?

Because of the diversity of domains and technologies in Life Sciences, data can be either "small" or "big data". As a consequence, the methods and technical solutions used for data analysis might differ. The characteristics of "big data" are often summarized by a growing list of ["V" properties: Volume, Velocity, Variety, Variability, Veracity, Visualization and Value](https://bigdatapath.wordpress.com/2019/11/13/understanding-the-7-vs-of-big-data/).

- The data analysis stage relies on the previous stages (collection, processing) that will lay the foundations for the generation of new knowledge by providing accurate and trustworthy data.
- The location of your data is important because of the need of proximity with computing resources. This can impact data transfer across the different infrastructures. It is worthwhile to compare the cost of the transfer of massive amounts of data compared to the transfer of virtual images of machines for the analysis.
- For the analysis of data, you will first have to consider the computing environment and choose between several computing infrastructure types, e.g. cluster, cloud. You will also need to select the appropriate work environment according to your needs and expertise (command line, web portal).
- You will have to select the tools best suited for the analysis of your data.
- It is important to document the exact steps used for data analysis. This includes the version of the software used, as well as the parameters used, as well as the computing environment. Manual "manipulation" of the data may complicate this documentation process.
- In the case of collaborative data analysis, you will have to ensure access to the data and tools for all collaborators. This can be achieved by setting up virtual research environments.
- Consider publishing your analysis workflow according to the FAIR principles as well as your datasets.
