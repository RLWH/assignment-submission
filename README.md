# Dataiku Takehome assignment
This repository contains the submission of the takehome assignment. 

## Assignment details
For this technical assessment, you have been tasked with identifying **characteristics that are
associated with a person making more or less than $50,000 per year**; the target variable for
your research question is the final column of the datasets.

As the data scientist on this project, you are to attempt to answer this question by constructing a
data analysis/modeling pipeline. Code submissions should be in Python and making the solution
easily readable and replicable by the team will give you additional marks. In the event you would
like to use a different language or tool, please ask. Considerations for your data analysis should
include, but are not limited to, the following:
- Data Preparation: Data cleaning, preprocessing, feature engineering, etc., that may aid
in improving data clarity & model generation.
- Exploratory Data Analysis: Numerical and/or graphical representations of the data that
may help inform insights and/or tactics for answering the research question of interest.
- Data Modeling: The building of a few competing models to predict the target variable.
- Model Assessment: A selection of the best model based on performance comparisons.
- Results: A concise summary of key findings, recommendations, & future improvements.

# About the submission
- [Part 1 - Data Cleansing.ipynb](Part 1 - Data Cleansing.ipynb) - Contains the data cleansing steps, including mapping the columns from metadata back to the dataframe, removing leading and trailing whitespaces, checking valid values of columns, etc.
- [Part 2 - EDA.ipynb](Part 2 - EDA.ipynb) - Contains the EDA of the dataset. Most of them are simply done by using boxplots (numerical values) and heatmaps (categorical values)
- [Part 3 - Model and results.ipynb] - Modelling. First use a CART decision tree to visualise the possible decision paths on splitting the data, and use ensemble models such as random forest and XGBoost to improve the model performance. Also contains Model Assessment and results.
- [Powerpoint] - [Link to presentation](https://docs.google.com/presentation/d/1ibWSr5gwRy40lZLXFVlIHUQHna6l3mIPXYwzyvVijew/edit?usp=sharing)