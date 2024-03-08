# Tanzania Water Wells Prediction

This repository contains the code and documentation for predicting the status of water wells in Tanzania, aiming to assist Wells of Life, an NGO operating in the region, in effectively identifying wells in need of repair. With millions of people struggling to access clean water, it's crucial to prioritize maintenance efforts efficiently. This project leverages machine learning algorithms to predict the condition of water wells accurately, allowing for optimized resource allocation and proactive intervention to improve access to clean water for communities in Tanzania.

## Problem Statement

The project addresses the challenge faced by Wells of Life in identifying water wells in need of repair. Many existing water points require maintenance or have failed entirely, leading to disruptions in water supply for communities in Tanzania. The lack of a systematic approach to assess the condition of water wells hampers effective prioritization of maintenance efforts. Therefore, the project aims to develop a classifier that utilizes various data points such as pump type, installation date, and other relevant variables to predict the condition of water wells accurately.

## Objectives

1. Develop insights into trends and patterns distinguishing between non-functional and functional wells.
2. Utilize straightforward analysis to pinpoint non-functioning wells and forecast well functionality based on available variables.

## Research Questions

1. How can historical data accurately predict water well conditions?
2. What challenges exist in predicting well conditions, and how can they be addressed?
3. How does the classifier's performance compare to existing methods?
4. What insights can the classifier provide for decision-making and resource allocation?

## Success Metrics

1. Ensure that newly constructed wells provide good quality water for communities.
2. Correctly identify the functionality of a well and determine its viability.
3. Generate a model that can accurately predict the quality status of wells in Tanzania with an accuracy of 80%.

## Data Understanding

### Data Source

The dataset is provided by Taarifa and the Tanzanian Ministry of Water. It includes various factors such as pump type, installation date, and management practices, allowing for the classification of pumps into three categories: functional, in need of repair, or non-functional.

### Evaluation

We evaluated several machine learning algorithms:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

While none of the models achieved the desired 75% accuracy, they provided valuable insights into predicting well conditions. We used confusion matrices and cross-validation to assess performance and identified class imbalance as a limitation affecting model performance.

## Repository Structure

- `data/`: Directory for storing datasets.
- `models/`: Directory for storing trained models.
- `notebooks/`: Jupyter notebooks for data exploration, model training, and evaluation.
- `src/`: Source code for data preprocessing, model training, and evaluation.
- `README.md`: Project overview and instructions for running code.
- `requirements.txt`: List of dependencies.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your_username/well-status-prediction.git
cd well-status-prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebooks in the `notebooks/` directory to explore data, train models, and evaluate performance.

4. Use the source code in the `src/` directory for data preprocessing, model training, and evaluation in your own scripts.

## Why Contribute?

The goal of this project, inspired by Learn.co's [Educational Content License](https://learn.co/content-license), is to continually improve the quality of the educational materials and code we provide. Contributions from the community are essential in maintaining and enhancing this project.

[...]

## License
This project contains educational content provided by the Flatiron School. The educational content is licensed under the terms of the Educational Content License provided by the Flatiron School. For more details on the license terms, please refer to the following link: [Flatiron Educational Content License](http://learn.co/content-license).

[...]
