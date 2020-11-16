# Kenya-Demographics-Health-Survey-KDHS--2014
---

> Author: Richard Taracha

> Date: 16/11/2020

![NYC Home Page Image](https://user-images.githubusercontent.com/67068918/98472046-59182b80-2201-11eb-940d-b18f930166e8.png)

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

Given a dataset, I performed data exploration and data wrangling (data cleaning and analysis) then came up with some appropriate recommendations. 

#### Technologies and Tools

- Pandas
- Numpy

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Project Deliverable
Deliverable is a python notebook that contains my solution:

* Notebook name: New York City Data Wrangling with Python.ipynb

Dataset Overview:
The dataset that was provided comes from the Bus Breakdown and Delay system which collects information from school bus vendors operating out in the field in real time. Bus staff that encounter delays during the route are instructed to radio the dispatcher at the bus vendor’s central office. The bus vendor staff are then instructed to log into the Bus Breakdown and Delay system to record the event and notify OPT. OPT customer service agents use this system to inform parents who call with questions regarding bus service. The Bus Breakdown and Delay system is publicly accessible and contains real time updates. All information in the system is entered by school bus vendor staff.

* Dataset name: hotel_bookings.csv
* Dataset Download Link: https://bit.ly/BusBreakdownDataset

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Recording the Experimental Design
1. Define the Research Question
2. Data Importation
3. Data Exploration
4. Data Cleaning
5. Data Preparation
6. Data Analysis

Given the dataset, I performed data exploration, data wrangling (cleaning and analysis) in an effort to come with appropriate recommendations. 

As a start while performing data analysis, I derived the following questions from the given dataset: 
1. Which bus companies that had the highest breakdowns?
2. What were the top 3 reasons for bus delays?
3. How many students were in the buses when they broke down?
4. Which were most frequent reasons for bus breakdowns?
5. What were the most frequent reasons for the bus running late?
6. What was the average delay time of each reason type?


[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Summary Of Findings

- From my analysis, most of the delays were caused by late returns from field trips
- Heavy traffic and mechanical problems are the most frequent reasons for bus delays.
- G.V.C., LTD, LEESEL TRANSPORTATION CORP (B2192) and PIONEER TRANSPORTATION CO	are the bus companies with the highest number of breakdowns.
- There were a total number of 58329 students on the bus when it broke down and a total number of 890829 on the bus when it was running late.

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Recommendations

From the above analysis, below are our recommendations:

* Since most of the delays were caused by Late return from Field Trips, it is recommended that the buses be rotated out to prevent breakdown i.e the buses going out for field trips should be on rotational basis.

* Heavy traffic is the most frequent reason for running late and hence either the roads be expanded to ease traffic or the number of vehicles plying that route should be regulated. Alternative routes may also be considered.

* An investigation into LITTLE RICHIE BUS SERVICE which is the bus company with the most breakdowns should be launched to understand the reason.

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)

---

## Author Information

- Twitter - https://twitter.com/Vycellous_Drum
- Website - https://richardtaracha.glitch.me/

[Back To The Top](#New-York-City-Bus-Breakdowns---Data-Wrangling-with-Python)


