# Heart Disease Analysis with Python & Seaborn.

Link: https://colab.research.google.com/#scrollTo=MIma91dkHO0E&uniqifier=1

This repository contains Python code for analyzing heart disease data using the Pandas library and visualizing the results with Seaborn. The code reads a CSV file containing heart disease data, performs data analysis and visualization, and creates various plots to gain insights into the dataset.

## Getting Started:

### Prerequisites

Before running the code, make sure you have the following Python packages installed:

- Python
- NumPy
- Pandas
- Seaborn

You can install them using `pip`:

```bash
pip install python numpy pandas seaborn
```
# Data
The code reads the heart disease data from a CSV file named heart.csv. Make sure you have this file in the same directory as the script.

# Code Description
The code includes the following sections:

1. Data Loading: The heart disease data is loaded from the CSV file using Pandas.

2. Gender vs Count: A distribution plot is created to visualize the count of gender (sex) in the dataset.

3. Age vs Count: A distribution plot is created to visualize the count of age in the dataset.

4. Resting BP, Cholesterol, Resting ECG, and Heart Disease vs Count: Distribution plots are created for each of these variables to visualize their counts.

5. Pie Charts: Pie charts are used to compare the ratios for sex, resting BP, chest pain type, resting ECG, and heart disease.

6. Violin Plots: Violin plots are used to analyze the variation and comparison of age, sex, and heart disease.

7. Heat Map: A correlation matrix and a corresponding heat map are generated to visualize the relationships between different variables in the dataset.

8. Pair Plot: A pair plot is created to show scatterplots between different pairs of variables in the dataset.

# Usage
You can run the code by simply executing the Python script. Make sure to have the required libraries installed and the heart.csv file in the same directory.

```
python your_script_name.py
```
# Contributing
Feel free to contribute to this project by opening issues or creating pull requests.

# License
This project is Licensed under the MIT License - see the LICENSE.md file for details.
