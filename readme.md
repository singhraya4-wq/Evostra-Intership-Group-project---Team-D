# Remote OK Job Market Analysis Project

## Project Overview

This project analyzes the remote job market using publicly available data from Remote OK.  
The objective is to identify hiring trends, in demand skills, job roles, locations, and company activity in the global remote work ecosystem.

The project follows a complete data science workflow including data collection, cleaning, analysis, visualization, and documentation.

## Data Source

The dataset is collected from the public Remote OK job listings feed.  
Only publicly accessible information is used.  
No authentication, private endpoints, or restricted content is accessed.

The data represents a snapshot of current remote job postings and may change over time.

## Project Objectives

1 Identify the most common remote job roles  
2 Analyze the most in demand skills  
3 Understand geographic distribution of remote jobs  
4 Explore hiring patterns across companies  
5 Present insights through clear visualizations  

## Project Structure

data  
raw  
Contains the raw dataset collected directly from the source  

data  
cleaned  
Contains the cleaned and preprocessed dataset  

notebooks  
01 Data collection  
02 Data cleaning and preprocessing  
03 Exploratory data analysis  
04 Data visualization  

visualizations  
Contains all generated charts saved as image files  

reports  
Methodology document  
Final analysis report  

README.md  
Project overview and usage instructions  

## Data Fields Used

Job title  
Company name  
Skills or tags  
Location  
Job type  
Date posted  
Job URL  

Missing optional fields such as skills, location, or job type are labeled as unknown to preserve dataset completeness.

## Tools and Technologies

Python  
Pandas  
Matplotlib  
Jupyter Notebook  
VS Code  

## How to Run the Project

1 Open the project folder in VS Code  
2 Open the notebooks directory  
3 Run the notebooks in order from data collection to visualization  
4 Generated datasets will be saved automatically  
5 Charts will be saved inside the visualizations folder  

## Key Insights Summary

Senior and engineering related roles dominate the remote job market  
General skill tags such as engineering, software, and support appear most frequently  
Most jobs are labeled remote with a strong concentration in the United States  
Many postings do not explicitly specify job type  
Companies like Cloudbeds, Chainguard, and Coingecko appear frequently  

## Limitations

The dataset represents a snapshot in time  
Job type information is often missing in the source  
Skills are represented as tags rather than structured technologies  
Some locations are broadly labeled as remote  

These limitations are documented and handled appropriately in the analysis.

## Ethical Considerations

Only publicly available data is used  
No personal or sensitive information is collected  
The project follows ethical web data usage practices  

## Conclusion

This project provides a structured and ethical analysis of the remote job market.  
It demonstrates real world data handling, analysis, and communication skills aligned with industry expectations.
