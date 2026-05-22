# SDS210 Project – ZüriWieNeu

Final assignment for SDS210 by Benjamin Kunz.

## Project Overview

This project analyzes public issue reports from the ZüriWieNeu platform using open data from the City of Zurich. 

The raw datasets are not included in this repository due to size. Please download them from the City of Zurich Open Data Portal. Links to the data are provided in the Notebook "Project_Start.ipynb".
The goal is to structure, explore, and analyze spatial urban data in a clear and reproducible workflow using Python.

The project combines:

- ZüriWieNeu report data (point data of reported issues)
- Statistical neighborhood boundaries of Zurich (polygon data)

By linking reports to neighborhoods through spatial operations, the notebooks answer several questions about how urban issues are distributed across the city.

## Structure
Every Notebook runs on its own. They are named after the Question they solve. 

## Questions

This project answers the following questions:

1. Which neighborhood receives the highest number of reports?
2. How does the number of reports vary between neighborhoods?
3. Which categories of problems are most common across the city?
4. How do the numbers of reports vary by category within a neighborhood?
5. How has the number of reports per category in a neighborhood developed over time?



## Results

Some of the findings include:

- Langstrasse has the highest number of reports in the dataset.
- Sihlfeld and Altstetten also stand out with high report counts.
- Across most neighborhoods, the most common category is Abfall/Sammelstelle (trash / waste collection).
- Only a few neighborhoods differ from this pattern, such as Escher Wyss, Friesenberg, and Hochschulen.
- Custom functions were created to:
  - generate pie charts showing the category distribution for any neighborhood
  - generate line plots showing how report categories change over time for any neighborhood



## Repository Structure

SDS210_Project_Benjamin_Kunz/
│
├── notebooks/
│   ├── Project_Start.ipynb
│   ├── first_and_second_question.ipynb
│   ├── third_question.ipynb
│   ├── fourth_question.ipynb
│   └── fifth_question.ipynb
│
├── environment.yml      
├── .gitignore            
└── README.md
