# Zomato Restaurant Dataset EDA

## Course
Big Data Analysis

## Project Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Zomato Restaurant Dataset. The analysis aims to explore restaurant characteristics, customer ratings, cuisines, restaurant costs, online delivery services, and table booking availability.

## Dataset Source

Zomato Restaurant Dataset

## Research Questions

1. Which cities have the highest number of restaurants?
2. Does online delivery affect restaurant ratings?
3. Does table booking affect restaurant ratings?
4. Is there a relationship between votes and ratings?
5. Do expensive restaurants receive higher ratings?
6. Which cuisines are the most common?

## Data Cleaning

The following preprocessing steps were performed:

- Checked missing values.
- Replaced missing values in the Cuisines column with "Unknown".
- Checked duplicate records.
- Removed unnecessary columns where applicable.
- Verified data types.

## Analysis Techniques

The following techniques were used:

- Descriptive Statistics
- Histograms
- Bar Charts
- Pie Charts
- Box Plots
- Scatter Plots
- Correlation Heatmap

## Main Findings

- Restaurant activity is concentrated in a limited number of cities.
- Most restaurants have moderate to high ratings.
- Customer votes show a positive relationship with ratings.
- Online delivery and table booking services may influence customer ratings.
- Some restaurants have significantly higher costs than others.
- Multiple factors contribute to restaurant performance.

## Requirements

- pandas
- numpy
- matplotlib
- seaborn

## How to Run the Project

1. Place the dataset file beside the notebook.
2. Install the required packages:

```bash
python -m pip install -r requirements.txt
```

3. Open the notebook:

```text
EDA_Homework.ipynb
```

4. Select the correct Python kernel.
5. Restart the kernel and run all cells.