# Project Name : 

**Analysis of Global COVID-19 Prevalence From The Year 2020 Till Date.**

---
# Project Objective: 

**With the sudden and seemingly outburst of COVID-19, barely is any nation or continent left unplagued. In this project, we want to understand the impact of COVID-19 on various nations and as well their various degrees of being affected.**

**We also want to  understand the global Effect of COVID-19 Pandmemic in order to fix Public Health Emergency Relapses.**

---
# Data Sourcing : 

**Our primary dataset to run this analyses was got from COVID-19 GitHub Data : https://aka.ms/30DLCOVID19GitHubData.
The Dataset contain subsets of time series form.**
The extracted data subsets for analysis were;

a. Global Confirmed Cases of COVID-19

b. Global Deaths from COVID-19

c. Global Recovered Cases from COVID-19
                  
# Data Transformation: 

**In order to make meaningful use of the avaialable datasets, I ensured that the format of the each subset of data was retained in the extension 'xlsx'.**

1) To begin with, there was web scrapping of the given Globally confirmed COVID-19 data subset from GitHub,into Excel. This was done by clicking on the Confirmed global COVID-19 subset >> clciking on its raw file >> then the url was copied from the browser.
2) Heading to Ms Excel environment, I clicked on the 'Data Tab' on Excel >> Then on  "From Web" , after which the copied url from Github is pasted and entered. The resulting column of data was transformed.
3) Then the first columns of the Confirmed global COVID-19 subset, were transformed into Headers and selected columns of "Country/Region, Latitude,Longitude,Date,Confirmed" were chosen via the Power Query Editor.
4) Other data subsets as well were scrappd from Github, and the same processes of the steps above were repeated on the Power Quwery Editor
5) Lastly, three different sheets were got and the "Merge" feature on Power Query editor was used to mrege the sheets, renaming the resulting sheet as "Consolidated",while loading and closing the Query editor.

**Transformation data:**
Analysis begun by ensuring that each column of the consolidated sheet is well formatted.
Afterward, relevant and needed columns were selected to create Pivot Tables of different variants, signifying the relationship of both top and bottom 5 countries with the highest confirmed,recovered and death cases of COVID-19.

Charts of diverse types were then used using the "Analyze Pivot Table" feature, to make up a new spreadsheet named "Dashboard".

---

# Findings : 

**"To every cause,there is an effect..." This section touches the 'effects' of our findings and reccomenations.**

 By sight, there is the recorded cumulative confirmed cases of  **_149,720,008,519_**
 
 Likewise, a total number of  **_2,633,869,299_**  was recorded as death cases.
 While the overall rate of death spans about **1.76%**

 ![THE DASHBOARD HEAd](https://user-images.githubusercontent.com/107119554/174418235-f5f19442-45a6-4ed9-937a-e04a94206466.PNG)

 
 Now,let's consider our first pair of visuals. It is glaring that of all the countries with the highest number of COVID-19 cases ,the **United States** 
 suffers the highest casualties, recording the most of the confirmed cases of the virus.
 
 While of the bottom 5 of nations with least cases, **North Korea** has the lowest record of COVID-19 cases, with precisely 32 cases. 


---
![Highest confirmed](https://user-images.githubusercontent.com/107119554/174417228-3aba5534-3398-466d-960d-d06c415717b5.PNG)

![Bottom 5 of confirmed cases](https://user-images.githubusercontent.com/107119554/174417600-8c069ee7-bfc1-4f2d-9099-a4150cfef1f0.PNG)

**In the third visual, it is seen that the cases of COVID-19 skyrocketed from 2020 into 2021 ranging from about 7 billion - 67 billion cumulative cases of the pandemic. While entering into 2022, there is a reduced increase in the number of cases.**


![Cumulative by Year](https://user-images.githubusercontent.com/107119554/174418213-ada61e53-bad4-41e8-bb4d-4a0a39bc80fc.PNG)

In addition, it is seen that the highest cumulative death cases is recorded in the **United States**. 
![5 HighesT Cumulative Death](https://user-images.githubusercontent.com/107119554/174912565-08d7a76a-93ad-4be5-a4fb-79e9b09d09d3.PNG)


Of the 10 least countries with death cases, we found out that about _five countries_ have no cumulative record of death;  Summer Olympics,
Holy See, Winter Olympics, Marshall Islands, Antarctica, Micronesia.  Apart from these, **North Korea** is seen to be the nation with the lowest cumulative record of death cases, with specifically 192 cases.
![Lowest deATH RATE](https://user-images.githubusercontent.com/107119554/174912969-8d562003-8e03-43fb-a846-fc9cc2a4d529.PNG)

Lastly on the plot of global recovery cases against month, we could observe a steady increase of recovery rate from January till July< before a sharp decline begins.
![Global Recovert by month](https://user-images.githubusercontent.com/107119554/174913259-34d6edf4-d9f9-4ac9-826d-552d7e7ead60.PNG)

![image](https://user-images.githubusercontent.com/107119554/174911639-446d10c3-0af9-419d-8c2a-f862adb56952.png)



# Recommendations: 

From Analysis and findings, the United States is the most plagued state, which is most likely due to the increase in the rate of migration as at the surge of the pandemic. 

Migration as well should be contained to effect reduction in number of cases. 

b.) Each country should ensure that shots of vaccines are taken to prevent an escalation of COVID-19 cases. 







