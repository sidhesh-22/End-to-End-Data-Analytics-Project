# End-to-End-Data-Analytics-Project

## Table of Contents

- [Project Overview](project-overview)
- [Data Source](data-source)
- [Major steps followed](major-steps-followed)
- [Insights and Findings](insights-and-findings)
- [Conclusion and further scope](conclusion-and-further-scope)


### Project Overview

This study looks at the relationships between various economic indicators and the cost of living as a strategy to improve knowledge of global socioeconomic events. Advanced data analysis and information visualization tools were used to evaluate data from three major databases: GDP, unemployment, income/spending, and migration. The stability of economic systems, along with concerns of living costs, and immigration play a key role in solving the status of global economic development.

![end_to_end_project](https://github.com/user-attachments/assets/835f8393-6988-4c85-a5e0-8882e7c3306c)



### Data Source

I've taken the datasets used in this project from Kaggle.


### Major steps followed

1. Fetching the unstructured (JSON) datasets from Kaggle.
2. Storing these unstructured datasets in MongoDB.
3. Data cleaning, preprocessing, and transformation.
4. Checking for outliers using boxplots
5. Exploratory Data Analysis.
6. Storing the individual clean datasets into PostgreSQL.
7. Merging all three clean dataframes in Python to form a final dataframe on the basis of common columns like country and year.
8. Exporting this combined dataframe into a csv file.
9. Loading this csv file into PowerBI for visualizations and transformation.
10. Building the final dashboard in PowerBI showing combined insights drawn from all individual datasets.


![apdv_project_steps](https://github.com/user-attachments/assets/511bcc30-1efa-4a99-8fd8-6421d0a62379)


### Insights and Findings

1. Immigration grew steadily between 1990 and 2020, but an acceleration after 2000 had a strong effect. This upward trend indicates that the countries of destination have greater opportunities for migration for the international migrant population to seek better living conditions or economic opportunities, among others.

![immigration plots](https://github.com/user-attachments/assets/b7f43e9d-9a78-462f-a454-ddf149084df8)


2. The histogram shows the top 10 nations by immigration (shown in this order), where the US is still the leader by far because of its strong economy and mass appeal. Germany and Russia follow, attracting migrants for their economic prospects and geographical closeness.


![top 10 countries](https://github.com/user-attachments/assets/bfe8a76f-5160-49f6-b78b-2c460f663f17)


3. In countries such as Lesotho, over 80% of GDP is represented by migrant remittances, the graph illustrates the measurable economic dependence derived from remittances.

![remittances plot](https://github.com/user-attachments/assets/460058cb-014f-4a93-a7aa-7cb95c56a727)


4. The dashboard features international and global trends, as well as a detailed overview of key economic and social indicators. Key economic indicators include GDP ($198K), GDP growth rate (2.30%), average cost of living ($4.12K), and average number of immigrants (7.59K). This means it examines the effects of immigration, geographical variations, and the relationship between cost of living and income.


Preview of the final PowerBI dashboard:


![APDV Final Dashboard](https://github.com/user-attachments/assets/018f617b-7cc0-410e-84a9-65d384741a1e)



### Conclusion and further scope

- The year-on-year fluctuating GDP has seen substantial growth yet also dramatic decline particularly in global crises such as 2020.
- According to comparisons across regions made for housing and educational costs, North America has the highest educational expenditures, while Africa has the lowest.
- Immigration also drives GDP and remittance flows and economic growth. However, remittances only account for 0.67% of GDP so they have almost no direct economic impact, reiterating the need to explore the broader advantages of immigration for labour and the development of societies.
- All in all, the results underscore the importance of finding a balance between economic growth and efforts to contain rising costs, reduce regional inequalities and make the most of immigration.
- This provides a foundation for sound policy to promote both global economic stability and improved standards of living.
