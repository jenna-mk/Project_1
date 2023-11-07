# Project 1: An Analysis of Work-Life Balance Scores Across 5 Dimensions of Lifestyle/Health
The purpose of this project is to analyze trends in a survey dataset that calculates a work-life balance score based on 24 questions across 5 dimensions of health. Our project looks at how each of these survey questions varies or correlates with the calculated work-life balance score, with age, and with work-life balance score category, which are defined as Poor (a score of less than 550), Good (a score between 550 and 680), or Excellent (a score above 680). The definition and scale for each question is shown in the analysis_definitions.txt file.

## Networking/Connection

Trends were analyzed relating the Work-Life Balance Scores with questions involving networking and connection. Specifically, the following questions were analyzed:

1.	With how many people do you interact with during a typical day?
2.	How man people are very close to you?
3.	How many new places do you visit?

The data on the results to each of these questions indicate that they each have a direct correlation with the calculated Work-Life Balance Score. In other words, the higher respondents answered each question, the higher, generally, their calculated Work-Life Balance Scores were. Questions 2 and 3 showed very close to a linear relationship between their responses and Work-Life Balance Score. The first question, regarding how many people the respondent interacts with on a typical day, showed a more interesting relationship where the Work-Life Balance Score tended to level off as the responses got higher.

When analyzed with a question involving typical daily stress, this data appears to show that there may be diminishing returns on happiness/work-life balance as someone interacts with more and more people. This may indicate that respondents experience a certain level of fatigue when it comes to daily interactions with other people.

## Healthy Mind 

Trends were analyzed relating the Work-Life Balance Scores with questions involving healthy mind practices. Specifically, the following questions were analyzed:

1. How much stress do you typically experience everyday?
2. How often do you shout or sulk at somebody?
3. In a typical day, how many hours do you experience "flow"?
4. How many hours do you spend everyday doing what you are passionate about
5. In a typical week, how many times do you have the opportunity to think about yourself?

The results of this analysis show that the above questions are directly related to work-life balance scores positively for the "good" mental activities (which includes flow, time spent on activities you are passionate about, and thinking about yourself/meditative activities) and negatively with the "bad" mental activities (which includes stress and shouting/sulking). There are 3 plots per question: raw work-life balance score vs question, question vs age group, and question vs work-life score category. While the scores and score categories consistently increased or decreased with increasing or decreasing values across the questions, there was no consistent correlation across age groups. 

## Expertise

Trends were analyzed relating the Work-Life Balance Scores with questions involving a person's ability to create something unique or expand their personal or professional expertise. Specifically, the following questions were analyzed:

1. How well do you complete your to-do lists?
2. How many recognitions have you received in your life?
3. How many remarkable achievements are you proud of?

The results of this analysis show that work-life balance scores and work-life score categories consistently increased with increasing values of the above questions for both males and females. There was no consistent trend across the questions for age group. The plots showing these relationships are in the expertise_analysis.ipynb notebook, and the summary statistics for this category is in the data folder in the expertise_summary.csv.

## Meaning 

Trends were analyzed relating the Work-Life Balance Scores with questions involving a person's life meaning, which includes their amount of compassion, generosity, and ability to live the life of their dreams. Specifically, the following questions were analyzed:

1. How many days of vacation do you typically lose every year?
2. How many people do you help achieve a better life?
3. For how many years ahead is your life vision very clear for?
4. How many times do you donate your time or money to good causes?
5. How sufficient is your income to cover basic life expenses?

The results of this analysis show that work-life balance scores and work-life score categories were consisently positively correlated with the responses for the questions involving helping others, donating, having a clear life vision, and sufficient income, and consistently negatively correlated with lost vacation days. There was no consistent trend across age categories. The plots showing these relationships are in the meaning_analysis.ipynb notebook, and the summary statistics for this category is in the data folder in the meaning_summary.csv.
