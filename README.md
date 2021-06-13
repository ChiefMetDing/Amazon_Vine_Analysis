# Amazon_Vine_Analysis
M16 Challenge

## Overview
The purpose of this analysis is to perform ETL process on Amazon reviews. The cleaned data is uploaded to pgAdmin connecting to an AWS RDS instance. The work also analyzed if there is any bias toward favorable reviews from Vine members in the dataset by calculating the 5-star percentages of Vine reviews and non-Vine reviews. This data process chose "Digital_Video_Games" as the dataset to be analyzed.

## Results
Q1: How many Vine reviews and non-Vine reviews were there?

A1: As shown in _figure 1_, there is 0 Vine reviews and 1,685 non-Vine reviews in the cleaned dataframe.

Q2: How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

A2: There is 0 5-star Vine review and 631 non-Vine reviews were 5-star.

Q3: What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

A3: The percentage of 5-star reviews in Vine reviews is not available, because the totel number of Vine review is 0. The percentage of 5-star reviews in non-Vine reviews is 37.45%.

![figure_1](https://user-images.githubusercontent.com/78275082/121792667-f12a2900-cbc5-11eb-88ea-0846c7c8e5d9.png)

_Figure_1: Vine Reviews_

![figure_2](https://user-images.githubusercontent.com/78275082/121792670-f6877380-cbc5-11eb-9f7b-4e24e6f790e1.png)

_Figure_2: non-Vine Reviews_

## Summary
Because there is no Vine review in the cleaned DataFrame, no evaluation on review bias is performed. To analyze Vine review data on the "Digital_Video_Games" dataset, tried performing Vine and non-Vine counts on the original dataset. The result shows that there is no Vine review in this dataset. Result shown below in _figure 3_.

![figure_3](https://user-images.githubusercontent.com/78275082/121792651-c8099880-cbc5-11eb-8bf3-d55efc1bd82a.png)
_Figure_3: Vine Reviews on Raw Dataset_

