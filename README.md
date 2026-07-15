# Machine Learning Methods for  the Titanic Dataset



## Exploratory Data Analysis

Exploratory Data Analysis (EDA) helps us see patterns in the data that are not obvious at
first. We use plots and simple statistics to understand the data better. It also helps us find
missing values, outliers and other important issues. The structure of the data gives us an idea
about how to continue the analysis in the next steps.

    Visualization Examples


### Graph 1
<img width="2400" height="1800" alt="Age_by_Survival_Status" src="https://github.com/user-attachments/assets/79ca5d20-6cb3-4ed8-b423-4ad1cfab1c81" />


Hypotheses

The following hypotheses are tested using a Mann-Whitney test:

$H_0$: There is no statistically significant difference in age between those who survived and those who did not survive.

$H_1$: There is a statistically significant difference in age between those who survived and those who did not survive.

In the given plot, p = 0.16 > 0.05. We cannot reject H0. Therefore, there is no statistically significant difference in age between those who survived and those who did not survive.


## Graph 2

<img width="2400" height="1500" alt="image" src="https://github.com/user-attachments/assets/51987d13-8b01-4102-a650-ac3715fc55f0" />


This graph shows that the age distributions of both genders are similar. When we look at thedensity, we can see that the highest concentration is between ages 20 and 30. The graph alsoshows the mean age, and it shows that males have a slightly higher average age than females.


## Graph 3
<img width="2400" height="1500" alt="image" src="https://github.com/user-attachments/assets/0c676a3c-53ff-40e6-83d6-e494c51d1e3e" />


This graph shows that the age distributions of people who survived and did not survive aresimilar. The highest density is between ages 20 and 30 for both groups. The graph also showsthe mean age, and it can be seen that people who did not survive are slightly older on average.In addition, younger people, especially children, have a higher survival rate. However, there isa large overlap between the two groups, so age alone is not a strong factor for survival.


## 1. Logistic Regression 
