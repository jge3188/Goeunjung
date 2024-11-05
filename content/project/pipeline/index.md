---
date: "2019-12-27T00:00:00Z"
external_link: ""
image:
  caption:
  focal_point: Smart
links:
- icon:
  icon_pack:
  name: Publication
  url: https://elifesciences.org/articles/74813
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/niksirbi/pcarpet
- name: Data
  url: https://doi.org/10.5281/zenodo.5565305
- icon: youtube
  icon_pack: fab
  name: Talk
  url: https://youtu.be/MoJ3HNUT4Lc
slides:
summary: This project establishes an automated geospatial data pipeline to streamline data acquisition, processing, and analysis, enhancing accessibility and reproducibility for comprehensive spatial studies on environmental and health impacts.
tags:
- NCC
- Geospatial Data Pipeline
- Geospatial Data
- Automation
- Geographic Variables
title: Geospatial Data Pipeline Construction
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

## Summary
Spatial geographic information databases play a critical role in various aspects, including the integration of location-based data, identification of risk factors, exploration of spatial patterns and correlations, and data visualization to support decision-making. However, the construction and utilization of spatial geographic information databases face numerous challenges: lack of consistency in spatiotemporal data formats, limitations of aggregate data and insufficient granularity, inaccuracies in location information, inconsistencies in coordinate systems, temporal discrepancies in infrastructure and data formats, variations in spatial resolution, and the challenge of handling large data volumes.

These issues result in significant time and cost expenditures for spatial data processing. Additionally, annual updates of spatial data necessitate a repetition of identical processing steps.

To address these challenges, it is essential to establish a comprehensive spatial geographic information data pipeline that automates the entire process from data acquisition to processing and information production. This pipeline should also include the creation of manuals and guidelines, along with a shared platform for broader accessibility.

Building such a spatial geographic information database enables researchers unfamiliar with spatial data to effectively use it. Even for experienced researchers, the pipeline can reduce repetitive data processing tasks and enhance the reproducibility of spatial data handling. Additionally, this shared analysis platform allows researchers to perform analyses without constraints on time or data capacity.

In this project, Amazon Web Services (AWS) was utilized, with ‘S3’ providing a cloud storage space for raw data and ‘Relational Database Service (RDS)’ supporting the storage and computation of relational geographic information data. This pipeline further includes the calculation of approximately 300 geographic variables using the processed data stored in the data storage. The analysis platform offers a user interface for immediate data querying, processing, and analysis through R Studio and Jupyter Lab.

In addition to data storage and processing, this pipeline includes the calculation of approximately 300 geographic variables, leveraging diverse spatial geographic information. These geographic variables enable a range of analyses, including spatial distribution analyses of environmental factors, exploration of spatial correlations with disease incidence and mortality rates, and spatial modeling of the health impacts of environmental risk factors. This expanded analytical capability allows researchers to gain insights into the spatial dynamics of environmental influences on health and other social factors.
