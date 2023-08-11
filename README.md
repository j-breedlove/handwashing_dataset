# Hand Washing Discovery

This project is a historical data analysis exploring the impact of hand-washing on birth and death rates. The data used in this analysis was collected between 1841 and 1849 at the Vienna General Hospital. This project offers a deep dive into the compelling history of Dr. Ignaz Semmelweis's discovery of the importance of hand-washing in medical practice.

## Setup and Context

Dr. Ignaz Semmelweis, a Hungarian physician born in 1818, worked at the Vienna General Hospital. At the time, people often attributed illnesses to "bad air" or evil spirits. However, in the 1800s, doctors began focusing more on anatomy and autopsy, making arguments based on data. Dr. Semmelweis suspected procedural issues at the Vienna General Hospital were causing high mortality rates from childbed fever (i.e., puerperal fever) in maternity wards. This project involves analyzing the same data that Dr. Semmelweis collected. 

![Dr. Semmelweis's Office](https://i.imgur.com/lSyNUwR.png)

1. Clone the repository:
```bash
git clone https://github.com/j-breedlove/handwashing_dataset.git
```
2. Change directory:
```bash
cd handwashing_dataset
```
## Preliminary Data Exploration

The first step of the analysis is data cleaning, which includes checking for NaN values and duplicates.

## Visualize the Total Number of Births 🤱 and Deaths 💀 over Time

This section is dedicated to visualizing the total number of births and deaths over time. This provides a clear picture of the overall trends in the hospital's birth and death rates during the period of study.

## The Yearly Data Split by Clinic

In this part of the analysis, the proportion of deaths at each clinic is calculated. This allows for a comparative study of different clinics within the hospital, helping to identify if certain clinics had higher or lower death rates.

## The Effect of Hand-washing

Finally, the core part of the analysis explores the effect of hand-washing. This involves creating a new column, "pct_deaths", which represents the percentage of deaths per birth for each row. The data is then split into two subsets: before and after Dr. Semmelweis's hand-washing order. The average death rates before and after June 1947 are calculated to analyze the impact of hand-washing. The results from this section provide quantitative evidence of the life-saving effect of hand-washing in a medical context.
