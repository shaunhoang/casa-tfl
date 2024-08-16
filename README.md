# Predicting Trip Attractiveness of Urban Activity Centres in Greater London using Explainable Machine Learning and Open Data

## Abstract

Leveraging explainable machine learning techniques (SHAP) on a finetuned XGBoost model, we were able to predict with high accuracy ($R^2>80\%$) the total arrivals by public transport in an area in Greater London, representing its trip attractiveness, from its amenity and connectivity features extracted from open data. The use of global and local SHAP explanations on the model provides valuable insights into not only feature importance but also the spatial heterogeneity of these features, which can be used to identify urban activity centres as destination hotspots and inform urban and transport planning decisions. The methodology can be extended to other localities where mobility datasets are not available since it relies on open data sources such as OpenStreetMap and the national census. Furthermore, this study serves as a foundation for future urban mobility research that aims to establish a comprehensive understanding of the factors that influence intracity travel demand and urban activity patterns.

## Code Structure

* **Data:** Briefly describe the data you're using, including the source, format, and any preprocessing steps. If you're not including the data in the repository due to size or sensitivity, mention this and explain where it can be obtained.
* **Scripts:** List the main scripts and their functions. For example:
    * `data_preprocessing.py`: Prepares data for analysis.
    * `model_training.py`: Trains and evaluates your model.
    * `visualization.py`: Creates plots and charts.
* **Models:** Explain the types of models you're using (e.g., machine learning, statistical) and any important considerations.
* **Results:** If applicable, provide a folder for storing intermediate results or outputs.

## Requirements

List the software dependencies and their versions:

* Python (3.x)
* Libraries:
    * NumPy
    * Pandas
    * Scikit-learn
    * Matplotlib
    * (Other libraries specific to your project)

## Installation

Provide clear instructions on how to set up the environment and run your code:

1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Install dependencies: `pip install -r requirements.txt`   

3. (Any other project-specific setup steps)

## Usage

Explain how to run the different scripts and provide examples:
