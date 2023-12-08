# Data Science Job Market

Getting a job data science job has been my goal and that I've been trying to achive since early 2023, and it's time consuming to read through all the job description to know the skills you need for the job. Over the pass few months, I have been actively searching and applying for data science jobs, and I found out the the skills companies are hiring for data science roles are quite large, depending on the company tech stack and data pipeline. So the initial goal of the project is to extract the skills given job description and perform an analysis on the skill extracted.

## Table of content

## Installation
All the package 
[How to install packages using pip]([https://www.google.com](https://packaging.python.org/en/latest/tutorials/installing-packages/)https://packaging.python.org/en/latest/tutorials/installing-packages/)  
```pip install requirements.txt```


### Data Collection

Most of data science jobs in Canada are posted on two major job board: Glassdoor and Indeed, so the data for this project will be collected from those 2 website.  
For this project, I collected over ... job posting over Canada in November 2023.  

Since Indeed and Glassdoor don't have API for developer to request the job listing on the site, I decide to collect the the data using web scraping.
  
![Recording 2023-12-08 at 10 21 59](https://github.com/alextr1602/data-science-job-market/assets/134574511/6857efc3-f12a-460d-9b24-ce3be464bc16)
    
Having a look at the website interface, we can see that Indeed and Glassdoor are dynamic websites, so I will use Selenium to collect data from these webs. The scraper are in file `indeed_scrape.ipynb` and `glassdoor_scrape.ipynb`  

## Code Structure (Too Long Don't Read)


