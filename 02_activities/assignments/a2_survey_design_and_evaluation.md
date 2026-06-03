# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#1`

Describe the purpose of your survey:
```
The purpose of this survey is to understand the factors contributing to high turnover among entry- and lower-level employees at a large technology company. The survey will collect information about employees’ satisfaction with compensation, workload, management, career development, workplace culture, and work-life balance. The results will help the Human Resources Department identify concrete changes that could improve employee retention and satisfaction.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
The target population is all current entry- and lower-level employees at the company, especially those working in departments where turnover has recently increased. The sampling frame is the company’s internal HR employee database, which includes job level, department, employment status, and company email address. The sampling units are individual employees selected from this HR database, and the observational units are also the individual employees who complete the survey. The survey will use a stratified random sampling strategy. Employees will first be grouped by department and job level, and then a random sample will be selected from each group. This strategy is appropriate because turnover may be caused by different factors in different departments or job levels, so stratification helps ensure that the sample represents the variety of entry- and lower-level employee experiences across the company.
```

Your 5-10 question survey:
```
1. How satisfied are you with your current role at the company?
   - Very satisfied
   - Somewhat satisfied
   - Neither satisfied nor dissatisfied
   - Somewhat dissatisfied
   - Very dissatisfied

2. How likely are you to look for a job outside the company within the next six months?
   - Very likely
   - Somewhat likely
   - Not sure
   - Somewhat unlikely
   - Very unlikely

3. Which of the following factors most affect your decision to stay at or leave the company? Select up to three.
   - Compensation
   - Benefits
   - Workload
   - Work-life balance
   - Relationship with manager
   - Career advancement opportunities
   - Company culture
   - Job security
   - Recognition or appreciation
   - Other: ________

4. How fairly do you think you are compensated for your work?
   - Very fairly
   - Somewhat fairly
   - Neutral
   - Somewhat unfairly
   - Very unfairly

5. How manageable is your current workload?
   - Very manageable
   - Somewhat manageable
   - Neutral
   - Somewhat unmanageable
   - Very unmanageable

6. How satisfied are you with the career growth and promotion opportunities available to you?
   - Very satisfied
   - Somewhat satisfied
   - Neither satisfied nor dissatisfied
   - Somewhat dissatisfied
   - Very dissatisfied
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type:
Cross-sectional sample survey; stratified probability sample.

2. Sample size:
Statistics Canada reports that approximately 50,000 field sample units were used, about 40,000 electronic questionnaire invitation letters were sent, and about 24,000 completed questionnaires were expected.

3. Target population:
Persons aged 15 and older living in the ten provinces of Canada, excluding full-time residents of institutions.

4. Sampling frame:
A combined frame using landline and cellular telephone numbers from the Census and administrative sources, plus Statistics Canada’s dwelling frame.

5. Survey modes:
Electronic questionnaire and CATI (computer-assisted telephone interviewing). Proxy responses were not allowed.

6. Timeline:
Data collection took place from September 4, 2018 to December 28, 2018.

7. Response rate:
The overall response rate was 41.9%.

8. Weights:
The file includes the person-level weight WGHT_PER. Bootstrap weights were also created for variance estimation.

9. Data processing:
Statistics Canada used generalized processing steps and utilities. Edits were performed automatically and manually, including family, consistency, and flow edits.

10. Cleaning, imputation, etc.:
Missing values were imputed mostly through donor imputation; mean imputation was used when donor imputation could not be used. Income data were linked to tax records when possible, and missing income information was imputed.

11. Sources of error:
The survey is subject to sampling error and non-sampling error, including coverage error, non-response, response error, and processing error.

12. Limitations / known biases:
Households without telephones were excluded from the survey population, which may create coverage bias. Non-response bias is also possible, though weights were adjusted to reduce it. Statistics Canada also notes that 2018 estimates should not be directly compared with previous iterations because the 2018 survey introduced an Internet response option and changed parts of the methodology.

13. Documentation and sources:
Use the Statistics Canada GSS GVP survey page and the PUMF Documentation and User Guide.

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
