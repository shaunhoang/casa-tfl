# Predicting Trip Attractiveness of Urban Activity Centres in Greater London using Explainable Machine Learning and Open Data

## Abstract

Leveraging explainable machine learning techniques (SHAP) on a finetuned XGBoost model, we were able to predict with high accuracy ($R^2>80\%$) the total arrivals by public transport in an area in Greater London, representing its trip attractiveness, from its amenity and connectivity features extracted from open data. The use of global and local SHAP explanations on the model provides valuable insights into not only feature importance but also the spatial heterogeneity of these features, which can be used to identify urban activity centres as destination hotspots and inform urban and transport planning decisions. The methodology can be extended to other localities where mobility datasets are not available since it relies on open data sources such as OpenStreetMap and the national census. Furthermore, this study serves as a foundation for future urban mobility research that aims to establish a comprehensive understanding of the factors that influence intracity travel demand and urban activity patterns.

## Highlights
TBD

## Methodology
#### Data preprocessing and feature enginnering
<img src="compile/images/preprocessing.png" alt="preprocessing">

#### Model selection, training and explanation with SHAP 
<img src="compile/images/methodology.png" alt="methodology">

## Repo Structure

1. **Compile:** Contains the LaTeX files and other elements needed to compile the final PDF document

1. **Code:** Contains the Jupyter notebook files for Python needed to reproduce the analysis:
    * `0_busto.ipynb`: ingests and preproceses TfL bus demand data
    * `0_numbat.ipynb`: ingests and preproceses TfL rail demand data
    * `1_ntwk_bus.ipynb`: builds bus network graph from raw data
    * `1_ntwk_rail.ipynb`: builds rail network graph from raw data
    * `1_poipop.ipynb`: ingests and preproceses POI data from OSM
    * `2_isochrone.ipynb`: creates isochrones as spatial units of analysis using OSMNx
    * `3_feature_agg.ipynb`: aggregates all features and target variables into one dataset for model training
    * `4_model_selection.ipynb`: tunes and evaluates prediction model
    * `5_model_training.ipynb`: trains chosen model on full dataset and analyses outliers
    * `6_shap.ipynb`: extracts and visualises SHAP values and explores further applications of SHAP values in identifying hotspots





