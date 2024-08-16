# Global Happiness Prediction using Machine Learning

This repository contains a machine learning project focused on predicting the happiness levels of countries based on various socio-economic factors. The project uses data from the World Happiness Report and implements different machine learning models to analyze and predict happiness scores.

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Contributing](#contributing)
- [Contact](#contact)

## Project Overview

The Global Happiness Prediction project aims to explore the factors that influence happiness across the world and to build predictive models that can estimate the happiness score of a country based on these factors. The project involves data preprocessing, exploratory data analysis (EDA), model selection, training, and evaluation.

## Data

The dataset used in this project is derived from the [World Happiness Report](https://worldhappiness.report/), which includes data on various indicators like GDP per capita, social support, healthy life expectancy, freedom to make life choices, generosity, and perceptions of corruption.

### Features:
- **Country**: Name of the country.
- **Region**: Geographical region of the country.
- **Happiness Score**: The happiness score of the country (target variable).
- **GDP per Capita**: Economic performance.
- **Social Support**: Social safety net.
- **Healthy Life Expectancy**: Life expectancy adjusted for health.
- **Freedom to Make Life Choices**: Freedom in decision-making.
- **Generosity**: Willingness to help others.
- **Perceptions of Corruption**: Level of corruption perception.

## Project Structure

The project is structured as follows:

```
GlobalHappinessPredictionML/
│
├── data/                    # Contains the dataset(s) used
├── notebooks/               # Jupyter notebooks for EDA and model development
├── src/                     # Source code for data processing and model training
├── models/                  # Saved models and performance metrics
├── results/                 # Results and visualizations
├── README.md                # Project readme file
└── requirements.txt         # Python dependencies
```

## Installation

To run this project locally, clone the repository and install the required dependencies.

```bash
git clone https://github.com/Prberte/GlobalHappinessPredictionML.git
cd GlobalHappinessPredictionML
pip install -r requirements.txt
```

### Dependencies:
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

## Usage

To use this project:

1. **Data Preparation**: The dataset should be placed in the `data/` directory. If not provided, you can download it from the World Happiness Report and preprocess it using the scripts provided in the `src/` directory.

2. **Exploratory Data Analysis (EDA)**: Start by exploring the data using the notebooks in the `notebooks/` directory. This will help you understand the data distribution and the relationships between features.

3. **Model Training**: Train the machine learning models by running the scripts in the `src/` directory. You can choose different algorithms such as Linear Regression, Decision Trees, or Random Forests, and evaluate their performance.

4. **Model Evaluation**: After training, evaluate the models using various metrics like RMSE, R², and visualize the results.

5. **Prediction**: Use the trained model to predict the happiness score of new data.

## Model Performance

Details about model performance, including metrics and visualizations, are stored in the `results/` directory. This includes comparisons between different models and hyperparameter tuning results.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the project's code of conduct.

## Contact

If you have any questions or need further information, feel free to reach out:

- Name: Prberte
- GitHub: [@Prberte](https://github.com/Prberte)
