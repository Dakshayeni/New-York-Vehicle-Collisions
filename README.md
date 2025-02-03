# New-York-Vehicle-Collisions Analysis
Statistical Analysis on New York Vehicle Collisions

## Overview
This project analyzes vehicle collision data in New York City to identify trends, patterns, and insights. The analysis includes data cleaning, exploratory data analysis (EDA), inferential statistics, and visualization of collisions based on factors such as time, location, and severity.

## Dataset
The dataset used in this analysis contains records of vehicle collisions in New York City. It includes information on date, time, location, contributing factors, number of persons injured/killed, and other relevant attributes.

## Features of the Analysis
- **Data Cleaning**: Handling missing values by replacing NaNs with median values.
- **Exploratory Data Analysis (EDA)**:
  - Number of collisions by day of the week.
  - Number of collisions by borough.
  - Grouping collisions by year and hour to observe trends.
  - Identifying high-risk areas and peak accident times.
- **Visualization**:
  - Bar charts and line plots to visualize trends.
  - Heatmaps for spatial distribution of collisions.
- **Inferential Statistics**:
  - Hypothesis testing to assess significant differences in collision trends across boroughs.
  - Correlation analysis between collision severity and contributing factors.
  - Regression modeling to predict accident frequency based on time and location data.
  - Chi-square tests, ANOVA and Bayesian Approach, Tukeys HSD to analyze categorical relationships (e.g., borough vs. accident severity).
- **Testing & Validation**:
  - Checked for missing values and replaced them where necessary.
  - Conducted outlier detection in numerical columns.
  - Verified the consistency of borough assignments based on latitude and longitude.
  - Cross-checked total injury and fatality counts with individual categories.
  - Ensured accurate removal of irrelevant columns while preserving key features.
  - Validated the accuracy of visualizations and statistical insights.

## Requirements
To run this notebook, install the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
1. Clone this repository:
```bash
git clone https://github.com/yourusername/New-York-Vehicle-Collisions
.git
```
2. Navigate to the directory:
```bash
cd New-York-Vehicle-Collisions

```
3. Open the Jupyter Notebook:
```bash
jupyter notebook "NewYork Vehicle Collision.ipynb"
```
4. Run all cells to execute the analysis.

## Results
- The dataset reveals peak collision hours and days.
- Certain boroughs report higher accident rates.
- Data visualization helps identify high-risk areas and trends.
- Inferential statistics confirm significant relationships between variables.
- Extensive testing ensures data integrity and reliability.

## Contribution
Feel free to contribute by adding new analyses, improving visualizations, or optimizing data cleaning techniques. Fork the repository and create a pull request with your changes.

## License
This project is open-source and available under the MIT License.

