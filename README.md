# Kenya-Demographics-Health-Survey-KDHS--2014
---

> Author: Richard Taracha

> Date: 16/11/2020

<!-- Alignment options!!!!! -->
<img align="right" width="350" height="350" src="https://github.com/TarachaR/-Exploring-the-Demographics-and-Health-Landscape-of-Kenya-The-2014-Kenya-Demographics-and-Health-Su/assets/67068918/62266fbf-4c96-48db-ba94-3e40761a90ad.gif">

<!-- ![10498-map-africa](https://user-images.githubusercontent.com/67068918/157054966-747112ef-f7b1-40e6-8c5e-a593a82fb02a.gif) -->

---

### Table of Contents
Sections headers used to reference locations of each destination:

- [External Data Source Validation](#external-data-source-validation)
- [Understanding The Context](#understanding-the-context)
- [Project Deliverable](#project-deliverable)
- [Recording the Experimental Design](#recording-the-experimental-design)
- [Summary Of Findings](#summary-of-findings)
- [Author Information](#author-information)

---

## External Data Source Validation

The data is originally from the Demographic and Health Surveys Program for the Kenya Demographics Health Survey (KDHS 2014). The data is provided and can be accessed via https://dhsprogram.com/data/dataset/Kenya_Standard-DHS_2014.cfm?flag=0/

> All personally identifying information has been removed from the data.

## Understanding The Context

The Demographic and Health Surveys (DHS) Program has collected, analyzed, and disseminated accurate and representative data on population, health, HIV, and nutrition through more than 400 surveys in over 90 countries.

As a Data professional you are tasked to determine the main factors that can help determine the number of total children ever born by a woman of reproductive age in Kenya. You are provided with the Kenya Demographics Health Survey (KDHS 2014) data set.

[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)

---

## Project Deliverable
Deliverable is a Python notebook with my statistical data analysis:

* Notebook name: Statistical Analysis of the Kenya Demographics Health Survey.ipynb

Dataset:
The Demographic and Health Surveys (DHS) Program URL: https://bit.ly/khds_dataset

The variables of interest in the data are:
| Column Name | Description |
| --- | --- |
| CASEID | Unique Case identifier |
| V010 | Respondents Year of Birth |
| V012 | Respondents current age |
| V025 | Type of residence |
| V024 | Region |
| V106 | Highest level of education |
| V152 | Age of household head |
| V201 | Total children ever born |

NB: The respondent for the provided data is a woman of a reproductive age

[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)

---

## Recording the Experimental Design
1. Load libraries
2. Load dataset with the variables of interest.
3. Answer the deliverables outlined below
4. Summarize findings.

**Deliverables:**
* Input the dataset provided and displayed the head(5) of the dataset with the above variables of interest only.
* Calculated the mean, median and mode for V012 , V152 and V201. Would I prefer mean or median for V201?
* Calculated the Range, IQR and standard deviation for V012 and V152. Commented on the variability of the variables.
* Ploted a histogram of V012 and V152 and explained the skewness.
* Created a frequency table for V024 and V106 then plotted a barchart for the two variables.
* Created a boxplot of V201 by (V025, V106, V024) separately.
* Created a scatter plot and computed the Pearson Correlation Coefficient between V201 and V012 explaining my findings.

Given the dataset, I performed data exploration, data wrangling (cleaning and analysis) and statistical data analysis in an effort to come with a summary of findings:

[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)

---

## Summary Of Findings
| Information | Details |
| --- | --- |
| Majority of respondents | Below 35 years of age |
| Majority of Household Heads | Below 50 years of age |
| Majority of respondents | From the Rift Valley region |
| Least respondents | From Nairobi |
| Most respondents' highest level of education | Primary level |
| Respondents with education levels beyond secondary school | Minority |
| More children born in | Rural areas than in urban areas |
| More children born to mothers with | No education |
| Nyanza Region leads in terms of total children born. | Nairobi Region is the last. |
| More children born to | Older women than to younger women. |


[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)

---

## Author Information

- Twitter - https://twitter.com/Vycellous_Drum
- Website - https://richardtaracha.glitch.me/

[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)


<h3 align="center">Made with ❤️ by Richard Taracha</h3>
