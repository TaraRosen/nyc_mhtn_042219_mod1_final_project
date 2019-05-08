
# Module 1 Final Project


## Introduction

This project consisted of cleaning, exploring and creating a pricing model using the King County, Washington property record dataset to predict sale prices as accurately as possible.

## Objectives

Predict Sale Prices


## The Dataset

King County House Sales dataset

The dataset can be found in the file
`"kc_house_data.csv"`, in this repo.

id                   Unique House Identifier
date                 Sale date
price                Price (Predicton Target)
bedrooms             Number of Bedrooms
bathrooms            Number of bathrooms
sqft_living          Square Footage
sqft_lot             Square Footage of the Lot
floorsTotal          Number of Floors
waterfront           Waterfront View
view                 Has Been Viewed
condition            Overall Condition of Property
grade                Overall Property Grade, Based on King County Grading System
sqft_above           Sqft Above Grade Square Footage
sqft_basement        Sqft Below Grade Square Footage
yr_built             Year Built
yr_renovated         Year Renovated
zipcode              Zip Code
lat                  Latitude Coordinate
long                 Longitude Coordinate
sqft_living15        Square Footage of interior housing living space for the nearest 15                            neighbors
sqft_lot15           Square Footage of the land lots of the nearest 15 neighbors


## The Process

- Visually Inspect The Data
     - Look for Missing Values

- Clean The Data
     - Handle Missing Values
     - Drop Irrelevant Data

- Visualize the Data

- Transform the Data

- Test Pricing Model

- Use Pricing Model!

## Results

- R-squared between features and price: 0.705
- RMSE: 0.0813


## Postmortem

The correlation between the chosen features and price is ok at 0.705.

The p-value for the intercept is high. I've been googling to try to find out why and if this is a problem but have not found any clear answers yet.

I'm still showing collinearity which means that my model still needs more work.

I think my kurtosis and skew values are where they should be.

I felt when I was finally getting the gist of what to do I ran out of time to continue to work on the project. I started to bin and make features such as waterfront and sqft_basement binary features but became a bit overwhelmed with the project deadline approaching.

I would like to return to this project once I have a bit more experience to see what improvements can be made.  
