# AI-Driven Media Investment Plan for E-Commerce Businesses

## more about me :-
✈️ [Follow Sagar Gaud](https://www.linkedin.com/in/sagargaud332/)

## Overview
This project involves creating an AI-driven media investment plan to optimize advertising strategies for e-commerce businesses. The solution leverages data from multiple advertising platforms to analyze performance and allocate budgets effectively. The key datasets used in this project are from Google Ads, Meta Ads, Facebook Ads, and Microsoft Ads, which provide insights into impressions, clicks, costs, conversions, and revenue.

## Datasets
The project utilizes two main datasets:

Dataset 1: Contains performance metrics for Google Ads, Meta Ads, and Facebook Ads.
Dataset 2: Contains performance metrics for Google Ads, Meta Ads, Facebook Ads, and Microsoft Ads.
Each dataset includes the following metrics:

## Impressions: Number of times the ad was shown.
Clicks: Number of times the ad was clicked.
Cost: The total cost of the ad campaign.
Conversions: Number of successful actions (e.g., purchases) resulting from the ad.
Revenue: Revenue generated from the ad campaign.
Reach: Number of unique users who saw the ad.
Files

```sh
googleads-performance.csv
metaads-performance.csv
facebookads-performance.csv
microsoftads-performance.csv
website-landings.csv
```

Data Analysis
Descriptive statistics were performed on each dataset to gain insights into the distribution, central tendency, and variability of various metrics across different advertising platforms.

Example: Descriptive Statistics
Google Ads Performance (Dataset 1)

```sh
       Impressions      Clicks         Cost    Conversions      Revenue
count   63.000000   63.000000   63.000000    63.000000    63.000000
mean  40122.333333 256.761905  331.476190    2.682540   560.390476
std   49019.670398 337.410563  372.158788    3.500888   936.234415
min       0.000000    0.000000    0.000000    0.000000     0.000000
25%    3805.500000   28.500000   50.200000    0.000000     0.000000
50%   26267.000000  189.000000  232.900000    0.800000   207.600000
75%   69707.500000  383.000000  611.600000    4.000000   599.300000
max  183496.000000 1172.000000 1525.000000   12.700000  3565.700000
```

Meta Ads Performance (Dataset 1)

```sh
        Impressions         Reach         Cost       Clicks  Conversions
count     32.000000     32.000000     32.000000    32.000000    32.000000
mean   24378.906250  18517.000000    151.381250   413.187500     3.312500
std    15559.574715  12814.279343     97.133932   259.847912     3.323665
min     4463.000000   3800.000000     45.200000    95.000000     0.000000
25%    12984.250000   9948.500000     88.275000   232.250000     1.000000
50%    21363.000000  16192.500000    143.100000   351.000000     2.000000
75%    31034.500000  23657.250000    198.625000   547.750000     4.000000
max    63573.000000  44893.000000    436.500000   959.000000    12.000000
```
## Tools and Tech Stack
Programming Languages: Python
Data Analysis and Visualization: Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn
Machine Learning: Scikit-learn
Data Storage: CSV files
Version Control: Git and GitHub

## Project Structure
data/: Contains all the CSV files with performance metrics.
notebooks/: Jupyter notebooks for data analysis and visualization.
scripts/: Python scripts for data processing and model training.
results/: Outputs and results from the analysis and models.
Requirements
Python 3.8+
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Installation

Data Analysis: Use the Jupyter notebooks in the notebooks/ directory to explore the datasets and perform descriptive statistics.
Model Training: Use the scripts in the scripts/ directory to preprocess the data and train machine learning models for optimizing media investment strategies.
Results: Review the outputs in the results/ directory to evaluate the performance of the models and strategies.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

### License
This project is licensed under the MIT License.

### Acknowledgments
Special thanks to NetElixir AIgnition for giving me this opportunity to represent my skills.
NetElixir AIgnition is an exciting and dynamic hackathon designed to bring together the brightest minds in AI and machine learning to tackle real-world challenges in digital marketing

### Contact
For any questions or inquiries, please contact us at sagargaud332@gmail.com
