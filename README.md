# AI for Climate Action – Predicting Global CO₂ Emissions


## Machine Learning Project | SDG 13: Climate Action


### Overview
This project demonstrates how Artificial Intelligence can support the United Nations Sustainable Development Goal 13 (Climate Action) by predicting global CO₂ emissions using a supervised machine learning model.

We use a Linear Regression approach to model CO₂ emission trends over time, showing how AI can help governments and researchers plan effective interventions in climate policy.


### Objective
- Address SDG 13 (Climate Action) by modeling the relationship between time and global CO₂ emissions.

- Provide a forecast of future emissions using historical data.

- Reflect on the ethical implications of applying AI to climate policy.


### Machine Learning Approach
- Type: Supervised Learning

- Algorithm: Linear Regression

- Toolkits: Python, Scikit-learn, Pandas, Matplotlib, Seaborn

- Target Variable: Global CO₂ emissions (in million metric tons)

- Feature: Year


### Dataset
A simulated dataset was used to mimic real global CO₂ emission patterns from 1960 to 2020.
In practical deployment, actual datasets would be sourced from:

- [World Bank Open Data](https://data.worldbank.org/)

- [UN SDG Indicators](https://unstats.un.org/sdgs/indicators/database/)

- [Kaggle Datasets](https://www.kaggle.com/)

### How It Works
1. Data Simulation: Generate a mock dataset resembling global CO₂ trends.

2. Preprocessing: Clean, structure, and split data into training and testing sets.

3. Model Training: Train a linear regression model to learn from historical data.

4. Prediction: Use the trained model to forecast emissions for unseen years.

5. Evaluation: Metrics such as MAE, MSE, and R² Score are used.

6. Visualization: A scatter plot contrasts predicted vs. actual values.

### Results
Metric	Value
MAE	≈ 224.46
MSE	≈ 66,831
R² Score	≈ 0.991

The model shows excellent performance and captures the emission trend with high accuracy.

### Ethical Considerations
- Bias: Global-level model may overlook local emission variances.

- Fairness: Encourages global perspective but calls for localized models.

- Sustainability: Empowers policy with predictive insights for emission control.

### Future Improvements
- Integrate real datasets via APIs (e.g., World Bank, NOAA).

- Build regional models for localized policy support.

- Deploy as a web app using Streamlit or Flask.

- Compare regression algorithms for improved forecasting.

### Files
- co2_forecast_model.ipynb – Jupyter Notebook with full model code.

- README.md – Project summary and guide.

- Presentation.pptx – Slides for 5-minute project demo.
