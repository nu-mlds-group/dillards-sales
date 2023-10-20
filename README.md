# MLDS-400 Group 2

## Weekly Updates

<details open>
  <summary>Week 5</summary>
<h3>At week 5, we are at stage 2 - Data Cleaning</h3>

Data Cleaning Details are listed as follows:

  1. We changed the datatype of each column of 5 tables to make sure the datatype of each column is correct.

  2. For the table of skuinfo, in the column of packsize, there are some pack sizes that do not make sense, including "G", "N/A", "Bizarre", "Promo test," and so on. In order to maintain the sku on record, we use the mode, which is 1, to replace these strange values. For detailed script, please visit: [here](2.Data_Cleaning/week5.pdf).

  3. This week, we spent a lot of time exploring the project research topic we want to explore:

      - According to the prices' different features (e.g. color, style, vendor, brand) to do a classification model so that we could use these classifications on products to predict the preferences of different customers.

      - Another possible direction is to help Dillards increase sales by investing in products combined with the features that are most welcomed and which ones are least welcomed. We could apply different discounts accordingly to increase sales revenue. This could be conducted through machine learning models like a random forest model.

  To Do:
  1. Continue with stage 2: Data Cleaning. Determine the project research direction and clean the datasets accordingly (e.g. drop unnecessary columns, select a subset of data to work with).

  2. After filtering the data we need, check the data thoroughly to see whether there are some bizarre and null values that don't make any sense, drop those rows, or replace them with the mean/mode depending on the variable type/distribution of the data.

  3. Choose the ML/clustering model we are going to work with.

  4. Start with EDA and analyze and investigate data sets and summarize their main characteristics, employed with data visualization.
</details>

<details>
  <summary>Week 4</summary>
  <h3>At week 4, we are at stage 1 - Data Overview & Description</h3>

  1. This week, we performed basic data cleaning and imported the dataset into the PostgreSQL server.

  2. we also made some summary statistics about the dataset. See more details [here](1.Data_Overview&Description/Week4.pdf).

To Do:

  1. We are going to continue working on data cleaning and understanding of the data, including basic EDA process.

  2. After having a decent understanding of the dataset, then we can proceed to brainstorm interesting questions related to machine learning so that we can work on them further for the rest of the weeks.
</details>


## Project Description
This project is to investigate a machine learning related question with the Dillard's point-of-sale dataset.

Suggested process to undertake:
1. Understand the data
2. Perform data exploration (number of SKUs, number of items per basket, number of stores, most frequently purchased items, busiest,stores, etc)
3. Find a machine learning related question to address
4. Feature selection and engineering
5. Modeling
6. Dashboards and story telling
7. ROI – make appropriate assumptions (support numbers used by using the web)



## Requirements
Every Friday by 5 pm each team has to post **a few-paragraph weekly update**. (The paragraph should be about the work from the previous week and not a summary from the beginning. It must also include the tasks for next week with clear goals.) If you miss it, 2% of the total grade is subtracted for each team member. You must posted it on github as part of a single document that has a date clearly visible for each update. The readme file on GitHub must have the project description with the tasks (what is already on canvas pertaining to your project). The first update must be done on Oct 13 at 5 pm.

Project deliverables posted on GitHub:

1. Deck of slides for a 15 minute presentation (Audience: chief data scientists, i.e., someone that is a manager but can also be technically dangerous); Assume that the audience does not know anything about the project.
2. Final report not to exceed 5 pages (it can have an appendix). Code should not be part of the report. Audience: Chief data scientists
3. An ROI analysis must be included in the report.
4. Scripts developed

## Grading criteria:

- Technical merit 30%
- Data visualizations 25%
- Final presentation 20%
- Final report (structure, content) 25%

Everything is due on Friday, December 5 at 5 pm. (At that time the repository will be cloned.)
