# Job Vacancy Web Scraping & Analysis Project

## Overview
This project demonstrates how web scraping can automate the sourcing of job vacancies for a recruitment agency. Manual searches for job postings are time-consuming and often miss opportunities. By extracting job data programmatically, the agency can deliver relevant openings faster and gain a competitive advantage for clients.

## Project Objectives
- Increase efficiency in sourcing job vacancies
- Improve the quality of job postings collected
- Provide actionable insights for clients

## Features
- Scrapes job postings from [Remote OK](https://remoteok.com/) using Python
- Extracts relevant fields: Job Title, Company, Location, Tags, and Date Collected
- Filters developer-related jobs using job titles and tags
- Visualizes:
  - Top companies hiring developers
  - Top locations for developer jobs
  - Most in-demand skills/tags

## Tools & Libraries
- Python 3
- Pandas
- Requests
- BeautifulSoup
- Matplotlib
- CSV

## How It Works
1. **Scraping**: The script fetches job postings from Remote OK's API.  
2. **Data Extraction**: Extracts job title, company, location, tags, and date collected.  
3. **Filtering**: Developer-related jobs are filtered using keywords in job titles and tags.  
4. **Visualization**: Creates bar charts for top companies, locations, and skills.  
5. **Output**: Saves the data to `job_postings.csv` and generates visualizations.

## Sample Analysis
- Total job postings scraped: 98  
- Developer-related jobs found: XX (after filtering by keywords and tags)  

### Key Insights
- High demand for developer roles like Software Engineer, Full Stack, Backend, and Frontend
- Remote jobs are common, with certain locations more frequent
- Most in-demand skills include Python, JavaScript, and full-stack frameworks

## Challenges & Solutions
- **Filtering Issues**: Initially filtering by “developer” returned zero results.  
  **Solution**: Used multiple keywords and included tags to capture relevant jobs.  
- **Data Cleaning**: Converted columns to strings to handle missing values (NaN).  

## Future Improvements
- Automate scraping daily for continuous updates  
- Store results in a database for historical tracking  
- Include salary, experience level, and job type for better analysis  
- Apply NLP for more accurate classification of job roles  

## How to Run
1. Clone this repository:
   ```bash
   git clone <your-repo-url>
