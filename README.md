# Project Name : Analysis of Global COVID-19 Prevalence From The Year 2020 Till Date.

---
# Project Objective: To understand the global effect of COVID-19 Pandmemic so as to Fix public Health Emergency Relapses.

---
# Data Sourcing : Our primary dataset to run this analyses was got from COVID-19 GitHub Data : https://aka.ms/30DLCOVID19GitHubData.
The Dataset contain subsets of time series form.
The extracted data subsets for analysis were;
a. Global Confirmed Cases of COVID-19
b. Global Deaths from COVID-19
c. Global Recovered Cases from COVID-19
                  
# Data Transformation: In order to make meaningful use of the avaialable datasets, I ensured that the format of the each subset of data was retained in the extension 'xlsx'.
1) To begin with, there was web scrapping of the given Globally confirmed COVID-19 data subset from GitHub,into Excel. This was done by clicking on the Confirmed global COVID-19 subset >> clciking on its raw file >> then the url was copied from the browser.

2) Heading to Ms Excel environment, I clicked on the 'Data Tab' on Excel >> Then on  "From Web" , after which the copied url from Github is pasted and entered. The resulting column of data was transformed.
3) Then the first columns of the Confirmed global COVID-19 subset, were transformed into Headers and selected columns of "Country/Region, Latitude,Longitude,Date,Confirmed" were chosen via the Power Query Editor.
4) Other data subsets as well were scrappd from Github, and the same processes of the steps above were repeated on the Power Quwery Editor
5) Lastly, three different sheets were got and the "Merge" feature on Power Query editor was used to mrege the sheets, renaming the resulting sheet as "Consolidated",while loading and closing the Query editor.





