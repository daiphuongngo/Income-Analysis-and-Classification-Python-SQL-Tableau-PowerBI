# Income-Analysis-and-Classification-Python-SQL-Tableau-PowerBI

## Overview:


## Target:

- Preprocessed, analyzed the Income background of all records in Python, SQL & visualized key variables in Tableau / Power BI to determine highlights, trends & predictions of Income types with ML, DL Classifiers

## Languages & Tools:

- Python

- SQL

- Tableau / Power BI

## Preprocess the data


## Exploratory Data Analysis


## Visualization


Dashboard - Age Distribution by Target Income Type, Work Type, Job

https://public.tableau.com/app/profile/dai.phuong.ngo/viz/IncomeAnalysisClassification-Story-AgeDistributionbyIncomeTypeWorkTypeJob/Story-AgeDistributionbyIncomeTypeWorkTypeJob

![Dashboard - Age Distribution](https://user-images.githubusercontent.com/70437668/144765740-8b23636e-e8ec-4b3b-9fc4-660088d45e9a.jpg)

Lower/Upper Quantiles & Meadians of both Target Income Types are not much different. Hence, observing the Age Distribution's Histogram, the Age groups dominating among Income < 50K over 80% of Average are from 15-40 years old. This could be due to early and middle stages of their career life and income. After the age of 45, there is a downturn for both Income Types. However, the dominant Age groups with Income >= 50K over 80% Average are from 30-55 years old. This could be people among elite groups with more stable income and wealthy classes. More specifically, the Age group of 40-44 years old plays the most significant role with both Income Types as their Total Working Hours Per Week rank 1st among all Age groups. Private sector contributes the most income of all Work Types with Craft Repair & Executive Managerial rank 1st & 2nd highest, respectively. Generally, high technical jobs put up higher income than less or non technical jobs. We can investigate further why Other Service are in the top well-paid ones by each job.

Dashboard - Relationship between Target Income, Capital Gain & Loss

https://public.tableau.com/app/profile/dai.phuong.ngo/viz/IncomeAnalysisClassification-Story-RelationshipbetweenTargetIncomeCapitalGainLoss/Story-RelationshipbetweenTargetIncomeCapitalGainLoss

![Dashboard - Relationship between Target Income, Capital Gain   Loss](https://user-images.githubusercontent.com/70437668/144766378-2bfe704d-cecf-45ee-bd06-0aad7d8a2322.jpg)

There is a strong relationship between the chosen features: Overall Income Type, Max Capital Loss, High Capital Loss, High Capital Gain. Max Capital gain. Hence, the higher the capital gain is, the higher the income will be and vice versa.
Next steps:
- Scale all features before building a Machine Learning model
- Conclude after visualizing the next correlation and distribution charts
- Outliers can be deleted easily on Tableau, but it might lead to a distortion in results, so checking the difference could be necessary.
