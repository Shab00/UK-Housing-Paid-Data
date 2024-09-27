# UK-Housing-Paid-Data

A Jupyter Notebook for analyzing and predicting UK housing prices using data science and machine learning techniques.

## UK Housing Paid Data Analysis

This repository contains the **UkHousingPaidDataMan.ipynb** and **ukHousingDataRevisted.ipynb** Jupyter Notebook, which is an ongoing project aimed at analyzing UK housing data. The project leverages various data science and machine learning libraries to provide insights and predictions about the UK housing market.

### Project Overview

The **UkHousingPaidDataMan.ipynb** notebook includes the following features:

- **Data Loading and Preprocessing**: Utilizes libraries such as pandas and numpy for data manipulation and preprocessing.
- **Exploratory Data Analysis (EDA)**: Uses seaborn for visualizing data trends and distributions, including new geolocation features that enhance our understanding of housing prices across different regions.
- **Geolocation Analysis**: Implements techniques to create geolocation features, allowing for more refined predictions based on geographical data.
- **Machine Learning Models**: Implements machine learning models using fastai, scikit-learn, and other libraries to predict housing prices.
- **Model Interpretation**: Employs tools like dtreeviz and treeinterpreter to visualize and interpret decision trees and random forests.

### Performance Metrics

Recent model scores using Mean Root Squared Error (m_rse) indicate an improvement in performance:
- Previous scores: **(0.415819, 0.591694)**
- New scores: **(0.382631, 0.544589)**

This demonstrates a positive trend in our model's predictive capabilities as we refine our approach and incorporate new features.

### Next Steps

The next step will be to explore the potential of neural networks to further enhance our predictions and model performance.

### Dependencies

The project requires the following libraries:

- numpy
- pandas
- fastbook
- fastai
- scikit-learn
- dtreeviz
- seaborn
- IPython

### Contributing

This is an ongoing project, and there are many features and improvements that can be added. Some of the areas that need more work include:

- **Data Enrichment**: Adding more datasets to enrich the analysis.
- **Feature Engineering**: Creating new features to improve model performance.
- **Advanced Models**: Implementing more advanced machine learning models.
- **Model Evaluation**: Enhancing model evaluation techniques and metrics.
- **Visualization**: Adding more visualizations to better understand the data and model predictions.

If you are interested in contributing, please fork the repository and submit a pull request with your changes. Any contributions are welcome!
