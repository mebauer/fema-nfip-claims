# Analyzing FEMA's National Flood Insurance Program (NFIP) Claims Data Using Python

*Author: Mark Bauer*

*Date Created: January 18, 2020*


# Introduction  

This analysis is designed explore FEMA's NFIP claims dataset.

You can find the raw code located in my notebook [nfip-claims-national.ipynb](https://github.com/mebauer/fema-nfip-claims/blob/master/nfip-claims-national/nfip-claims-national.ipynb).

Additionally, you can find and download the data dictionary provided by FEMA as as excel file (.xlsx) located in my data-dictionary folder [data-dictionary](https://github.com/mebauer/fema-nfip-claims/tree/master/nfip-claims-national/data-dictionary).

I am new to the open source community, so feedback is very welcome! Thank you for taking the time to read my notebook.


# Objective

Analyzing FEMA's National Flood Insurance Program (NFIP) Claims Dataset by Year of Loss and State.


# About the Dataset

FIMA NFIP Redacted Claims Data Set.

*Federal Insurance & Mitigation Administration National Flood Insurance Program (FIMA NFIP) Redacted Claims Dataset*

*This dataset represents more than 2,000,000 claims transactions. Due to the file size we recommend using Access, SQL, or another programming/data management tool to visualize and manipulate the data, as Excel will not be able to process files this large without data loss. Please note that there is a lag of 45 to 60 days for current data to be released. This data set is derived from the NFIP system of record, staged in the NFIP reporting platform and redacted to protect policy holder personally identifiable information.*

Souce: [*FIMA NFIP Redacted Claims Data Set*](https://www.fema.gov/media-library/assets/documents/180374). 


# Data Wrangling

1. Download the NFIP Redacted Claims Dataset.

2. Group the claims dataframe by **year of loss** and **state**. 


# How to Download the NFIP Redacted Claims Dataset

Data can be accessed from FEMA's Open Data Portal [here](https://www.fema.gov/media-library/assets/documents/180374).

Extract the NFIP Redacted Claims Dataset from this webpage. We need to download it directly as a zipfile, and then unzip the file once it is in our Dowloads folder. A screenshot of the claims dataset is below.

![FEMA Open Data Screenshot](images/fema-opendata-011820.png)


# Results

![Sample Figure](figures/nfip-claims-by-year-count.png)
**Figure 1. Number of NFIP Claims by Year of Loss**


![Sample Figure](figures/nfip-claims-by-year-amount.png)
**Figure 2. Amount Paid on Total NFIP Claims by Year of Loss**


![Sample Figure](figures/nfip-claims-by-year-average.png)
**Figure 3. Average Amount Paid on Total NFIP Claims by Year of Loss**


![Sample Figure](figures/nfip-claims-by-year-subplots.png)
**Figure 3. Plots of Number, Total Amount Paid, and Average Amount Paid of NFIP Claims by Year of Loss**


![Sample Figure](figures/nfip-claims-by-year-count-top10.png)
**Figure 4. Top 10 Number of NFIP Claims by Year of Loss**


![Sample Figure](figures/nfip-claims-by-year-amount-top10.png)
**Figure 5. Top 10 Amount Paid on Total NFIP Claims by Year of Loss**


![Sample Figure](figures/nfip-claims-by-year-average-top10.png)
**Figure 6. Top 10 Average Amount Paid on Total NFIP Claims by Year of Loss**


![Sample Figure](figures/nfip-claims-by-state-count.png)
**Figure 7. Number of NFIP Claims by State**


![Sample Figure](figures/nfip-claims-by-state-count-top10.png)
**Figure 8. Top 10 Number of NFIP Claims by State**


![Sample Figure](figures/nfip-claims-by-state-amount.png)
**Figure 9. Amount Paid on Total NFIP Claims by State**


![Sample Figure](figures/nfip-claims-by-state-amount-top10.png)
**Figure 10. Top 10 Amount Paid on Total NFIP Claims by State**


# Overall Conclusions


