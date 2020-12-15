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
Location of Triple-Negative Breast Cancers: Comparison with Estrogen Receptor-Positive Breast Cancers on MR Imaging:
Kim WH, Han W, Chang JM, Cho N, Park IA, Moon WK (2015) Location of Triple-Negative Breast Cancers: Comparison with Estrogen Receptor-Positive Breast Cancers on MR Imaging. PLoS ONE 10(1): e0116344. <https://doi.org/10.1371/journal.pone.0116344> 

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

# Comments about the Data
## Assumptions
The excel sheet that I was given was relatively straight-forward with its information. However, there were a few things that I had to make assumptions on. One of those things is the fact that I am still unclear of how they normalized their x, y, and z distance data to form the x, y, z normalized data. Another thing that I would not have understood without looking at their paper, was how the x, y, and z locations were determined.

## Reproducibility
I found their graphs to be pretty reproducible since I was also able to generate similar graphs using the data given. I also found their data to be pretty tidy with only minute changes made which I have described earlier in this markdown report. However, most of the paper is graphs so I was on my own with the visuals that I created. I tried to make my data more reproducible by commenting extensively to explain why I did each step. This code however is still vary specific to this project and would have to be reformatted some to make it more usable for different datasets. 

