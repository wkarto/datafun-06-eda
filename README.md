# Python Exploratory Data Analysis project
# datafun-06-eda
```
Exploring Data Analytics with Python
```
# .gitignore file
```
# Ignore project virtual environment in the .venv folder
.venv/

# Ignore Visual Studio Code settings in the .vscode folder
.vscode/

# Ignore macOS specific files
.DS_Store

# checkpoints folder

 .ipynb_checkpoints/

```
# Create and Manage virtual environment
```
py -m venv .venv

.venv\Scripts\Activate
```

## import dependencies 
```

Create a file in the root folder of your repo (same level as the README.md) named requirements.txt with the following packages:
jupyterlab
pandas
pyarrow
matplotlib
seaborn

Using following command to import packages:

py -m pip install -r requirements.txt

```

# Git commands used: 
```
git pull
git add .
git commit 
git push
```

# Dataset Description

https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv 

## Overview
```
This dataset contains measurements and attributes of various penguin species collected from different islands
in the Antarctic region. The primary focus is on the Adelie, Chinstrap, and Gentoo penguin species.
It includes key physical characteristics that can be used for ecological studies, species identification,and research related to environmental changes.
```

## Attributes
```
Species: The species of the penguin (e.g., Adelie, Chinstrap, Gentoo).

Island: The specific island where the penguin was observed (e.g., Torgersen, Biscoe, Dream).

Bill Length (mm): The length of the penguin's bill measured in millimeters.

Bill Depth (mm): The depth of the penguin's bill measured in millimeters.

Flipper Length (mm): The length of the penguin's flipper measured in millimeters.

Body Mass (g): The weight of the penguin measured in grams.

Sex: The sex of the penguin (Male, Female, or missing data).
```

## Steps for EDA: 
```
Data Acquisition
Initial Data Inspection
Initial Descriptive Statistics
Initial Data Distribution for Numerical Columns
Initial Data Distribution for Categorical Columns
Initial Data Transformation and Feature Engineering
Initial Visualizations
Initial Storytelling and Presentation
```

## Project conclusion
```
This EDA highlights the essential insights into the penguins data. It is concluded that, habitat preferences,
physical characteristics, and potential ecological factors influence the distribution of penguin species.
```
