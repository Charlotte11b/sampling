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

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
This survey aims to identify the primary drivers of turnover among entry- and lower-level employees at the company, including factors related to compensation, workload, management, growth opportunities, and workplace culture. Results will also help determine whether turnover drivers differ across departments, locations, and job families.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population is all current and recently separated employees in entry- and lower-level roles who worked at the company within the past 12 months.

Sampling frame is the HRIS records for (a) current employees in eligible levels and (b) employees who voluntarily resigned in the past 12 months (including email contact and department/job family/location metadata).

Sampling units are individual employees (current or separated).

Observational units are individual survey responses (one response per employee).

Overall sampling strategy would be to use a stratified random sample to ensure representation across key groups likely associated with turnover (e.g., department, location, job family, tenure bands such as <6 months, 6–12 months, 1–2 years). Oversample groups with the highest turnover or small departments to enable comparisons, and apply weighting during analysis to reflect the true employee composition. Offer the survey to all eligible recent leavers, but only sample current employees.
```

Your 5-10 question survey:
```
Q1. Employment status (Select one)
☐ Current employee (entry/lower-level)
☐ Left the company voluntarily in the past 12 months
☐ Left the company involuntarily in the past 12 months

Q2. Department / function (Select one)
☐ Engineering / Product
☐ Data / AI
☐ Sales / Customer Success
☐ Operations
☐ HR / Finance / Admin
☐ Other (please specify): __________

Q3. Tenure (Select one)
☐ Less than 3 months
☐ 3–6 months
☐ 6–12 months
☐ 1–2 years
☐ More than 2 years

Q4. Overall satisfaction (Select one)
☐ Very dissatisfied
☐ Dissatisfied
☐ Neutral
☐ Satisfied
☐ Very satisfied

Q5. Top factors affecting your decision to stay or leave (Select up to 3)
☐ Compensation and benefits
☐ Workload or stress
☐ Manager relationship / supervision quality
☐ Career growth / promotions
☐ Training and onboarding
☐ Team culture / belonging
☐ Work-life balance / scheduling
☐ Role clarity / expectations
☐ Remote/hybrid policy or commute
☐ Recognition and feedback
☐ Other (please specify): __________

Q6. Manager support and feedback (Select one)
Statement: “My manager provided clear expectations, support, and regular feedback.”
☐ Strongly disagree
☐ Disagree
☐ Neutral
☐ Agree
☐ Strongly agree

Q7. Career growth and development (Select one)
Statement: “I had a clear and realistic path for growth (skills, mentorship, promotion) at this company.”
☐ Strongly disagree
☐ Disagree
☐ Neutral
☐ Agree
☐ Strongly agree

Q8. Workload manageability (Select one)
☐ Not manageable
☐ Somewhat unmanageable
☐ Neutral
☐ Somewhat manageable
☐ Very manageable

Q9. Compensation competitiveness (Select one)
How would you rate your compensation relative to similar roles elsewhere?
☐ Much lower
☐ Slightly lower
☐ About the same
☐ Slightly higher
☐ Much higher
☐ Not sure

Q10. Most important improvement (Open-ended)
What is the single most important change the company could make to improve satisfaction and retention for entry- and lower-level employees?
Response: ________________________________________________
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
Source:
https://www150.statcan.gc.ca/n1/pub/45-28-0001/2020001/article/00037-eng.htm 
https://www150.statcan.gc.ca/n1/en/catalogue/45250011
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234 

1. Sample type: Cross-sectional with a stratified design employing probability sampling. The stratification is done at the province/census metropolitan area (CMA) level. Information is collected from one randomly selected household member aged 15 or older, and proxy responses are not permitted.
2. Sample size: A field sample of approximatively 50,000 units was used. Among them, about 40,000 invitation letters to the electronic questionnaire were sent to selected households across Canada. A completion of 24,000 questionnaires was expected. 
3. Target population: All persons 15 years of age and older living in the ten provinces of Canada. It excludes full-time (residing for more than six months) residents of institutions.
4. Sampling frame: This survey uses a frame that combines landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada's dwelling frame. Records on the frame are groups of one or several telephone numbers associated with the same address (or single telephone number in the case a link between a telephone number and an address could not be established). 
5. Survey mode(s): electronic questionnaire (online) and CATI (computer-assisted telephone interviewing); respondent chooses English or French
6. Timeline: 2018-09-04 to 2018-12-28
7. Response rate: 41.9%
8. Weights: Person-level analysis weight WGHT_PER (basic weight for person-level estimates). Bootstrap weights are provided for design-based variance estimation. Weighting includes adjustments for the rejective (non-volunteer) sub-sampling, and calibration/adjustment so weighted distributions align with external totals (e.g., age-sex by province; and income distribution alignment noted in documentation).
9. Data processing: generalized processing environment (SSPE); Automated and manual edits at macro/micro levels: family, consistency, and flow edits; CATI includes built-in range/flow edits; head office review resolves issues and interviewer comments. 
10. Cleaning, imputation, etc: Imputation was carried out in nine steps. The first step consisted of imputing personal income and family income. The next three steps involved imputing the formal volunteering variables in the master file. Steps five and six were imputing the informal volunteering variables in the master file. Finally, the last three steps involved imputing variables in the donation file and the solicitation methods in the master file.
11. Sources of error: Sampling error, coverage error (e.g., households without telephones / not covered by frame), nonresponse at household and individual stages, response error, and processing error.
12. Limitations, known biases, etc: Households without telephones are excluded from the surveyed population (potential coverage bias). Low response rate (41.9%) increases risk of nonresponse bias despite weighting adjustments. Because 2018 introduced an internet response option and other methodological updates, StatsCan advises that it is not appropriate to compare 2018 GSS GVP results with previous iterations.
13. Link to documentation and any additional sources used: Questionnaires and reporting guides: https://www23.statcan.gc.ca/imdb/p3Instr.pl?Function=getInstrumentList&Item_Id=1183690&UL=1V&. 
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
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
