# Kenya-Demographics-Health-Survey-KDHS--2014
---

> Author: Richard Taracha

> Date: 16/11/2020

<!-- Alignment options!!!!! -->
<img align="right" width="350" height="350" src="https://github.com/TarachaR/Kenya-Demographics-Health-Survey-KDHS--2014/assets/67068918/45a40220-dcd8-48d9-ab2b-602cd1cbf1e8.gif">

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

#### Technologies and Tools

- Pandas
- Numpy
- Matplotlib
- Seaborn

[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)

---

## Project Deliverable
Deliverable is a Python notebook with my statistical data analysis:

* Notebook name: Statistical Analysis of the Kenya Demographics Health Survey.ipynb

Dataset:
The Demographic and Health Surveys (DHS) Program URL: https://bit.ly/khds_dataset

The variables of interest in the data are:
- CASEID: Unique Case identifier
- V010: Respondents Year of Birth
- V012: Respondents current age
- V025: Type of residence
- V024: Region
- V106: The highest level of education
- V152: Age of household head
- V201: Total children ever born

NB: The respondent for the provided data is a woman of a reproductive age

[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)

---

## Recording the Experimental Design
1. Load libraries
2. Load dataset with the following variables:
    
    * CASEID : Unique Case identifier
    * V010 : Respondents Year of Birth
    * V012 : Respondents current age
    * V025 : Type of residence
    * V024 : Region
    * V106 : Highest level of education
    * V152 : Age of household head
    * V201 : Total children ever born
    
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
* Majority of the respondents are below 35 years of age.
![A Histogram showing the Respondents Current Age](https://user-images.githubusercontent.com/67068918/99255760-719dcc80-2825-11eb-8255-f9d06a8881be.png)

* Majority of Household Heads are below 50 years of age.
![A Histogram showing the Age of the Household Head](https://user-images.githubusercontent.com/67068918/99256118-f4268c00-2825-11eb-8308-e75994a6df3c.png)

* Majority of the respondents are from the Rift Valley region while the least are from Nairobi.
![Bar Chart Showing The number of respondents by Region](https://user-images.githubusercontent.com/67068918/99261392-b9285680-282d-11eb-8af0-a61df746b593.png)

* Most of the respondents have attained Primary level of education as their highest level of education. Those with education levels beyond secondary school make up the minority.
![Bar Chart Showing Highest level of Education](https://user-images.githubusercontent.com/67068918/99267351-e62c3780-2834-11eb-8f7c-d37407c9dfd1.png)

* More children are born in rural areas than in urban areas.
![Box plot of Total children ever born vs Type of residence](https://user-images.githubusercontent.com/67068918/99261684-19b79380-282e-11eb-931a-fed3347089af.png)

* More children are born to mothers with no education.
![Box plot of Total children ever born vs The highest level of education](https://user-images.githubusercontent.com/67068918/99267912-969a3b80-2835-11eb-96ed-716ab704f24a.png)

* Nyanza Region leads in terms of total children born. Nairobi Region is the last.
![Box plot of Total children ever born by Region](https://user-images.githubusercontent.com/67068918/99262038-8a5eb000-282e-11eb-8232-2d0b8a89422f.png)

* More children are born to older women than to younger women.
![Total children ever born vs Respondents current age](https://user-images.githubusercontent.com/67068918/99268483-45d71280-2836-11eb-9cf9-2d832653813b.png)

[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)

---

## Author Information

- Twitter - https://twitter.com/Vycellous_Drum
- Website - https://richardtaracha.glitch.me/

[Back To The Top](#Kenya-Demographics-Health-Survey-KDHS--2014)

