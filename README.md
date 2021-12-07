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


### Dashboard - Age Distribution by Target Income Type, Work Type, Job

https://public.tableau.com/app/profile/dai.phuong.ngo/viz/IncomeAnalysisClassification-Story-AgeDistributionbyIncomeTypeWorkTypeJob/Story-AgeDistributionbyIncomeTypeWorkTypeJob

![Dashboard - Age Distribution](https://user-images.githubusercontent.com/70437668/144766516-88f5ba6c-00a3-4523-ade3-efef00a4115c.png)

Lower/Upper Quantiles & Meadians of both Target Income Types are not much different. Hence, observing the Age Distribution's Histogram, the Age groups dominating among Income < 50K over 80% of Average are from 15-40 years old. This could be due to early and middle stages of their career life and income. After the age of 45, there is a downturn for both Income Types. However, the dominant Age groups with Income >= 50K over 80% Average are from 30-55 years old. This could be people among elite groups with more stable income and wealthy classes. More specifically, the Age group of 40-44 years old plays the most significant role with both Income Types as their Total Working Hours Per Week rank 1st among all Age groups. Private sector contributes the most income of all Work Types with Craft Repair & Executive Managerial rank 1st & 2nd highest, respectively. Generally, high technical jobs put up higher income than less or non technical jobs. We can investigate further why Other Service are in the top well-paid ones by each job.

### Dashboard - Relationship between Target Income, Capital Gain & Loss

https://public.tableau.com/app/profile/dai.phuong.ngo/viz/IncomeAnalysisClassification-Story-RelationshipbetweenTargetIncomeCapitalGainLoss/Story-RelationshipbetweenTargetIncomeCapitalGainLoss

![Dashboard - Relationship between Target Income, Capital Gain   Loss](https://user-images.githubusercontent.com/70437668/144766517-c3152cb8-8311-4833-8001-1afa20067a6b.png)

There is a strong relationship between the chosen features: Overall Income Type, Max Capital Loss, High Capital Loss, High Capital Gain. Max Capital gain. Hence, the higher the capital gain is, the higher the income will be and vice versa.
Next steps:
- Scale all features before building a Machine Learning model
- Conclude after visualizing the next correlation and distribution charts
- Outliers can be deleted easily on Tableau, but it might lead to a distortion in results, so checking the difference could be necessary.

### Dashboard - Relationship between Capital Gain, Loss & Working Hours by Country

https://public.tableau.com/app/profile/dai.phuong.ngo/viz/IncomeAnalysisClassification-Dashboard-RelationshipbetweenCapitalGainLossWorkingHoursbyCountry/Dashboard-RelationshipbetweenCapitalGainLossWorkingHoursbyCountry?publish=yes

![Dashboard - Relationship between Capital Gain, Loss   Working Hours by Country](https://user-images.githubusercontent.com/70437668/144966436-031cb6f3-6a3f-42ef-bfc3-566b89e600ca.png)
