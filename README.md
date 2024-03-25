# Classic-Composers
Classical Composers Analysis

Project Overview

This project explores the careers and lifespans of classical music composers from various nationalities. Utilizing a dataset that includes information such as composer name, nationality, date of birth, date of death, and duration of their longest piece, we aim to uncover patterns related to productivity, lifespan, and the impact of nationality on a composer's career.

Key Questions

How does the lifespan of composers correlate with their productivity?
Do composers from certain nationalities tend to have longer or shorter career spans?
Is there a relationship between the era in which a composer lived and the length of their compositions?
Dataset

The dataset was sourced from Kaggle and includes the following columns:

Composer: Name of the composer
DateOfBirth: Date of birth
DateOfDeath: Date of death
Nationality: Nationality of the composer
LongestPiece: Duration of the longest piece recorded (in minutes)
NameOfLongestPiece: Name of the longest piece
Methodology

Data Preparation
The data was cleaned to remove any missing values and to standardize the format of dates. 

Analysis
We used Python's Pandas and Seaborn libraries for data manipulation and visualization. The analysis involved:

Calculating lifespan and career length for each composer
Grouping data by nationality to assess the average and standard deviation of career lengths and ages at death
Visualizing the data using bar plots, scatter plots, histograms and box plots to compare across nationalities and identify outliers
Key Findings
Lifespan and Productivity: Preliminary analysis indicates a weak correlation between lifespan and the number of compositions, suggesting that longevity may not be a significant factor in a composer's productivity.
Career Length by Nationality: Certain nationalities show a trend towards longer career spans, with Finnish and American composers having the longest average careers.
Composition Length Across Eras: The Baroque era featured the longest average composition lengths, while the Modern era saw a decrease in average composition length.
Conclusion

Our analysis provides insights into the factors that may influence a classical composer's career and output. While nationality and historical era play a role in career length and composition length, individual variability remains high, underscoring the unique nature of artistic creativity.

Future Work

Further research could explore the influence of education, socio-economic status, and specific historical events on a composer's career. Additionally, a more detailed analysis of composition types and subjects across different eras could yield further insights.

How to Use This Repository

analysis.ipynb: Jupyter notebook containing the full analysis, including data cleaning, exploration, and visualization
data/: Directory containing the dataset used in the analysis
Dependencies

Python 3.8+
Pandas
Seaborn
Matplotlib
Altair
Installation

To set up the analysis environment, run:

bash
pip install pandas seaborn matplotlib altair
License This project is licensed under the SD3-CLAUSE
