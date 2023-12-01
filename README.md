# Life Expectancy Prediction Project

## Overview

Welcome to the Life Expectancy Prediction Project! This project aims to predict life expectancy based on various features utilizing machine learning techniques. The dataset used in this project is sourced from [Life.csv](data/life.csv).

## Table of Contents

1. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
3. [Correlation Analysis](#correlation-analysis)
4. [Feature Selection](#feature-selection)
5. [Model Building](#model-building)
6. [Usage](#usage)
7. [Dependencies](#dependencies)
8. [Author](#author)
9. [License](#license)

## Data Cleaning and Preprocessing

In this section, we perform the following steps:

1. Read the data from 'data/life.csv'.
2. Drop unnecessary columns and clean column names.
3. Handle missing values.
4. Encode categorical variables.
5. Save the cleaned data to 'cleaned.csv'.

## Exploratory Data Analysis (EDA)

Explore the data distribution and relationships through various visualizations, such as histograms, boxplots, and geographical mapping.

## Correlation Analysis

Analyze the correlation between variables and create a heatmap to visualize the correlation matrix.

## Feature Selection

Identify and drop highly correlated features to avoid multicollinearity.

## Model Building

Build a regression model to predict life expectancy using selected features. Split the data into training and testing sets.

## Usage

To reproduce the analysis and results:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/life-expectancy-prediction.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:

   ```bash
   jupyter notebook
   ```

   Open and run the notebook `life_expectancy_prediction.ipynb` in your Jupyter environment.

   Ensure you have Python 3.x, Jupyter Notebook, and the required Python packages installed.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Required Python packages (install using `pip install -r requirements.txt`)

## Author
[Chandraparsad]('https://github.com/chandraparsad3')

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
