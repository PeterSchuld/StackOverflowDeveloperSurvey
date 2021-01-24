# StackOverflowDeveloperSurvey
# Udacity Data Science Nanodegree - Write a Data Science Blog Post
Project No. 1 in the Udacity Data Science Nanodegree Winter 2020-2021

All the project code is contained in the Jupyter notebook StackOverflowSurvey_PeterSchuld_final.


#### Project Description ####
The dataset that we wrangle, analyze and visualize is StackOverflow developer survey. We use the 2018 and 2020 surveys to analyse changes in the popularity of programming languages. Two of the survey questions are asking about programming languages users have done extensive development work in over the past year, and which languages they want to work in over the next year. We use the 2020 survey to analyse correlations between programming languages and between other frameworks, libraries, and tools (i.e. technologies) users have done extensive development work in over the past year. Furthermore, we filter the data for respondants who perform the developer role of Data Scientist or Machine Learning Specialist. We analyse what additional developer roles they perform, what languages they prefer and what technologies they use.

Next, we use a linear machine learning model to find coefficients with significant impact on the salaries of professional developers in the United States.  We have used the answers (i.e. observations) from professional developers in the USA (subset of 7096 observations) to train a linear machine learning model with Python sklearn. We have used 5 numerical variables like work experience (in years) and we have mapped 26 of the survey's categorical variables as input for the ml model. It accounts for the variation (dispersion) of 50% of the salaries of professional developers in the USA. The r² score is above 0.5 for both the train data (70% of observations) and the test data (30% of observations). 

#### Data ####
Since 2011, Stack Overflow, a popular Q&A site for developers, has surveyed a large number of users. The annual surveys consist of questions with numerical answers (e.g. age, salary) and of questions with categorical answers from multiple choice options ( "choose one" or "choose all that apply" ). The 2020 survey contains 61 questions (i.e. variables) and nearly 65,000 users from all over the world took part. Notably, the 2020 survey was conducted in February, before the World Health Organization declared the coronavirus outbreak to be a pandemic. 

#### The following packages (libraries) need to be installed #### 
Pandas, NumPy, sklearn, matplotlib, seaborn
