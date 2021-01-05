### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The Anaconda distribution of Python should be the only necessary thing required to run the code here. It should run without issues when using Python 3.

## Project Motivation<a name="motivation"></a>

### Business Understanding
For this project, I was interestested in using Stackoverflow's 2017 Annual Developer Survey to look at the data regarding whether people who mainly work from home report liking or disliking their jobs, along with whether these same people feel they are well paid. In other words, whether working from home is worth it. To do this, I asked several questions:

1. What proportion of respondents work from home most of the time?
2. What proportion of respondents like their jobs?
3. What proportion of respondents think they are well paid?
4. What proportion of respondents that mostly work from home like their jobs?
5. What proportion of respondents that mostly work from home and like their jobs feel well paid?

### Data Understanding
The data for this project came from Stack Overflow and comprises both the survey questions and the responses gathered. Each row of the dataset represents a single respondent, while the columns represent the questions asked. Much of the data is categorical with smaller portions being numerical and text. Not all respondents answered all questions so there is some missing data in the dataset. 

Udacity owns the full set of files related to this project, so I have not made them publicly available here, but parts of the analysis regarding this data can be viewed in the project.

### Data Preparation
During data preparation, I gathered and assessed the dataset. Next, I cleaned the data, paying particular attention to the columns on which my project focused, and using methods available in the Numpy and Pandas Python libraries. In particular, I dropped rows with missing values in the relevant columns I examined from the dataset.

### Data Modeling
Although my project does not focus on modelling, I included an AdaBoost Classifier at the end of the project which utilizes GridSearchCV to tune the model's hyperparameters for an optimal model. My goal was to see how well the data could be used to predict whether a person could be classified as liking their job.

### Evaluation of the Results
The results of the analysis indicate that, of the respondents who reported working from home most of the time, about 80% reported scores which show that they like their jobs. Additionally, of the proportion of people who reported both working from home most of the time and liking their jobs, about half of them stated that they believe themselves to be well paid. In other words, for them, working from home was worth it.

My findings as a result of the code can be found at the Medium post [here](https://steveellingson.medium.com/happy-with-home-work-bf0e42d02ff3).

## File Descriptions <a name="files"></a>
There is one notebook available here that logically shows the work related to the questions I set out to answer. Markdown cells and comments are used to indicate the reason for the code that follows.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Licensing for the data and other information can be found at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).
