# Observing tumor severity, size, and location data of triple negative breast cancers in comparison to estrogen-receptor positive breast cancers.
Capstone Project for TFCB 2020
 
Jazmine A. Snow

December 16, 2020

# Description
 - This project compared the locational data of triple negative (which I will be referring to as "trip_neg") breast cancers with estrogen-receptor positive (which I will be referring to as "er_pos") breast cancers using MRI techniques. 

# [Raw Data](../main/raw-data)
[Tumor Location Data](../main/raw-data/tumor%20location%20raw%20data_final.xls)
  - This file was the one that was provided by the original researchers for this dataset.

# [Edited Data](../main/edited-data)
## Published Paper
Location of Triple-Negative Breast Cancers: Comparison with Estrogen Receptor-Positive Breast Cancers on MR Imaging <https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0116344>
  - I have provided the published paper that this dataset was taken from above for referrence. 

## [Edited Tumor Location Data](../main/edited-data/tumor-location_edited-data_csv.csv)
- For this file, I tidied the data a little by cleaning up the column names, and adding NA to the size column when a size was not recorded. 
- I also converted this file from an  excel spreadsheet to a csv file to use for my analysis. 

# Questions
## Question 1
- Did the severity of the tumor change between the trip_neg tumors and the er_pos tumors?
   - To answer this question, I used python to compare the histology grade within these two tumor subsets. 

## Question 2
- Did the average size of the tumor change between the trip_neg tumors and the er_pos tumors?
   - To answer this question, I used R to calculate and compare the average tumor size between these two tumor subsets.

## Question 3
- Were there locational differences between the trip_neg tumors and the er_pos tumors?
   - To answer this question, I used R to compare the three different location data given (quadrants, mediolateral location, and anteroposterior location) between these two tumor subsets. 

# Results
## Question 1

## Question 2
![Question 2](../main/figures/tfcb-capstone_question02_tumor-size-comparison_bar-graph-figure.jpg)

## Question 3

# Conclusions
## Question 1

## Question 2

## Question 3

# Comments about the Data
## Reproducibility
## Assumptions
