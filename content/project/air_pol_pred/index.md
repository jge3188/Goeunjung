---
date: "2020-12-27T00:00:00Z"
external_link: ""
image:
  caption:
  focal_point: Smart
links:
- icon:
  icon_pack:
  name:
  url:
- icon:
  icon_pack:
  name:
  url:
- icon:
  icon_pack:
  name:
  url:
- icon:
  icon_pack:
  name:
  url:
slides:
summary: "This project aims to predict air pollution concentrations at locations across South Korea where direct measurements are unavailable."
tags:
- NCC
- Air Pollution
- Prediction
- Modeling
- Universal Kriging
- Geospatial Data Pipeline
title: "Air Pollution Predictive Modeling"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

## Summary
This project aims to predict air pollution concentrations at locations across South Korea where direct measurements are unavailable. Using the **Universal Kriging** (UK) model, we estimate the annual concentrations of key air pollutants—**PM10, PM2.5, O3, and NO2**. The UK model leverages observed pollutant concentrations at monitoring sites and incorporates spatial and environmental characteristics represented by geographic variables, along with spatial autocorrelation, to predict concentrations at unmonitored locations.
The observational data consists of annual air pollution measurements collected from air quality monitoring stations nationwide. Additionally, the model integrates 320 geographic variables, derived from spatial data processing pipelines, which capture factors related to air pollution levels, such as road networks, elevation, population density, land use, and vegetation index (NDVI). To manage the high dimensionality of these variables, we employ **Partial Least Squares (PLS)** regression to reduce the dataset to 2–3 primary predictive components, which serve as inputs for the UK model. This dimensionality reduction optimizes model performance by focusing on the most relevant predictors.
In many cases, our team utilizes this model to estimate air pollution exposure for cohort study participants based on their residential locations. This process involves an initial geocoding step, where participants' address information is converted into geographic coordinates. Subsequently, approximately 320 geographic variables are calculated for each residential location. These variables are then reduced to key components via PLS, which are used as inputs in the UK model to estimate pollutant concentrations for individual residences. Through this project, we enhance the precision of individual exposure assessments by estimating air pollution concentrations directly at individuals' residential locations rather than relying on the concentrations from nearby monitoring sites. This approach enables more accurate evaluations of personal exposure and contributes to more precise health effect assessments related to air pollution exposure.
