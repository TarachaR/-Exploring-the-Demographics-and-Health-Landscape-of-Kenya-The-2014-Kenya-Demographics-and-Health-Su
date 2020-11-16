# Kenya-Demographics-Health-Survey-KDHS--2014
---

> Author: Richard Taracha

> Date: 16/11/2020

![kenya2_6_700x400](https://user-images.githubusercontent.com/67068918/99253290-8f693280-2821-11eb-8973-fe37870bddb8.png)

---

### Table of Contents
Sections headers used to reference locations of each destination:

- [External Data Source Validation](#external-data-source-validation)
- [Understanding The Context](#understanding-the-context)
- [Project Deliverable](#project-deliverable)
- [Recording the Experimental Design](#recording-the-experimental-design)
- [Summary Of Findings](#summary-of-findings)
- [Recommendations](#recommendations)
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

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Project Deliverable
Deliverable is a Python notebook with my statistical data analysis:

* Notebook name: Statistical Analysis of the Kenya Demographics Health Survey.ipynb

Dataset:
The Demographic and Health Surveys (DHS) Program URL: https://bit.ly/khds_dataset

The variables of interest in the data are:
CASEID: Unique Case identifier
- V010: Respondents Year of Birth
- V012: Respondents current age
- V025: Type of residence
- V024: Region
- V106: The highest level of education
- V152: Age of household head
- V201: Total children ever born

NB: The respondent for the provided data is a woman of a reproductive age

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

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

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Summary Of Findings
* Majority of the respondents are below 35 years of age.
![A Histogram showing the Respondents Current Age](https://user-images.githubusercontent.com/67068918/99255760-719dcc80-2825-11eb-8255-f9d06a8881be.png)

* Majority of Household Heads are below 50 years of age.
![A Histogram showing the Age of the Household Head](https://user-images.githubusercontent.com/67068918/99256118-f4268c00-2825-11eb-8308-e75994a6df3c.png)

* Majority of the respondents are from the Rift Valley region while the least are from Nairobi.
![Bar Chart Showing The number of respondents by Region](https://user-images.githubusercontent.com/67068918/99261392-b9285680-282d-11eb-8af0-a61df746b593.png)

* Most of the respondents have attained Primary level of education as their highest level of education. Those with education levels beyond secondary school make up the minority.
![Bar Chart Showing The number of respondents by Region](https://user-images.githubusercontent.com/67068918/99261562-f0970300-282d-11eb-84f6-0b28c9a5bf54.png)

* More children are born in rural areas than in urban areas.
![Box plot of Total children ever born vs Type of residence](https://user-images.githubusercontent.com/67068918/99261684-19b79380-282e-11eb-931a-fed3347089af.png)

* More children are born to mothers with no education.
![Bar Chart Showing Highest level of Education](https://user-images.githubusercontent.com/67068918/99261902-5c796b80-282e-11eb-88c3-d1abf751ab05.png)

* Nyanza Region leads in terms of total children born. Nairobi Region is the last.


[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Recommendations

From the above analysis, below are our recommendations:

* Majority of the respondents are below 35 years of age:

* Heavy traffic is the most frequent reason for running late and hence either the roads be expanded to ease traffic or the number of vehicles plying that route should be regulated. Alternative routes may also be considered.

* An investigation into LITTLE RICHIE BUS SERVICE which is the bus company with the most breakdowns should be launched to understand the reason.

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Author Information

- Twitter - https://twitter.com/Vycellous_Drum
- Website - https://richardtaracha.glitch.me/

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)


