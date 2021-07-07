# Covid_19_SQL_DataExploration
Demonstration of various SQL codes to explore updated (as of 7/6/21) Covid-19 data.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)



## General Information
- Downloaded COVID-19 data from https://ourworldindata.org/covid-deaths.  Contains up to the day data on COVID-19 statistics.
- Edited excel file into two sheets:  One with Covid Death statistics, and the other with Covid Vaccination statistics.  Saved both files as CSV's
- Uploaded CSV's into PGAdmin4 (my postgreSQL software), which was a huge pain in the butt.  Had to make a blank column with all of the appropriate columns (26 for Deaths, 38 for Vaccinations).
- Used SQL code to find the following:  (please look at document for specific code)
  - Total Cases vs Total Deaths
  - Total Cases vs Population
  - Global Numbers
  - Total Population vs Total Vaccinations
  - CTE's
  - Temporary Tables
  - View to store data for later visualization.


## Technologies Used
- Excel
- PGAdmin4 (postgreSQL software)

## Acknowledgements
- Alex the Analyst, youtuber.  This project is directly based on his Portfolio Project series.
- Jose Portilla, Head of Data Science (Pierian Data Inc.)  Shout out to Jose for creating 'The Complete SQL Bootcamp 2021: Go from Zero to Hero' Udemy Course.  Was super useful for understanding the concepts behind the code here.
