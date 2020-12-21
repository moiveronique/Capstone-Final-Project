# Capstone-Final-Project
## WEEK 4 Assignment Requirements:
For this week, you will required to submit the following:

A description of the problem and a discussion of the background. (15 marks) <br />
A description of the data and how it will be used to solve the problem. (15 marks)



## Analysis on break and enter crime in Toronto from 2014 to 2019
### Introduction and background
The aim of this project is to find a safe and secure location for living or opening a business in Toronto, Canada. Specifically, this report will be targeted to the break and enter crime situation over the past 5 years in different neigborhood in Toronto.

We will make use of our data science tools to analyse data and focus on the trend of each borough from 2014 to 2019, and will focus on the 2019 data specifically to choose the safest and most dangerous boroughs by analysing crime data and short listing the neighbourhood.

### Data
Based on definition of our problem, factors that will influence our decision are:

1. finding the safest and most dangerous borough based on crime statistics in 2019 <br />
2. finding the trend of beak and enter crime for each borough <br />

We will be using the geographical coordinates of Toronto to plot neighbourhoods in a borough that is safe and in the city's vicinity, and finally cluster our neighborhoods and present our findings. <br />
Following data sources will be needed to extract/generate the required information: <br />
Part 1: Using a real world data set from Tronto Police Service website: A dataset consisting of the crime statistics of each Neighbourhood in Toronto along with location, recorded year, premise type. <br />
dataset URL: https://data.torontopolice.on.ca/datasets/break-and-enter-2014-to-2019/data
https://prod-hub-indexer.s3.amazonaws.com/files/d9b3dd6402454c379ba57994230aabea/0/full/3857/d9b3dd6402454c379ba57994230aabea_0_full_3857.csv <br />
Part 2: Gathering additional information of the list of officially categorized boroughs in Toronto from Wikipedia.: Borough information will be used to map the existing data where each neighbourhood can be assigned with the right borough. <br />
dataset URL: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M <br />
Part 3: Creating a new consolidated dataset of the Neighborhoods, along with their boroughs, crime data and the respective Neighbourhood's co-ordinates.: This data will be fetched using OpenCage Geocoder to find the safest and most dangerous borough and explore the neighbourhood by plotting it on maps using Folium and perform exploratory data analysis.

