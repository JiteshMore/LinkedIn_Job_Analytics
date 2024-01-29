# LinkedIn Job Analytics

LinkedIn Job Analytics is a data-driven project that utilizes Python, Beautiful Soup, and Selenium to scrape and analyze job information from LinkedIn. This project offers insights on industry trends, top job locations, and company analysis, providing users with valuable information for optimizing their job search strategies.

## Prerequisites

Before running the LinkedIn Job Analytics project, make sure you have the necessary installations and setups for the following tools and libraries:

- **Web Scraping using Python:**
  - Selenium: Python library for automating web browsers.
  - Time: Python library for handling time-related functions.
  - Pandas: Powerful data manipulation library in Python.
  - NumPy: Fundamental package for scientific computing in Python.

- **Google Chrome Browser Driver:**
  - Install the appropriate Chrome browser driver.

- **Python Jupyter Notebook:**
  - Used for data cleaning and data separation tasks.
  - NumPy and Pandas: Required libraries for working with numerical arrays and structured data within Jupyter Notebook.

- **Excel:**
  - Utilized for data storage purposes.

- **SQL:**
  - Used for data analysis to extract insights from the collected data.
  - Basic SQL knowledge is necessary to perform data querying and analysis tasks.

- **Tableau:**
  - A powerful data visualization tool for creating interactive and visually appealing dashboards and reports.

## Project Structure

### Web Scraping (Folder)

- `chromedriver.exe`: Chrome browser driver used for web scraping.
- `main.py`: Python file responsible for scraping data from the website.
- `scrapped raw data.csv`: Excel file containing the raw extracted data from the portal.

### Data Cleaning of Scrapped data.ipynb using Python

Details about the data cleaning process performed on the scraped data.

### Data (Folder)

- `jobs.csv`: Contains details about the job.
- `company.csv`: Contains company details.
- `details.csv`: Contains details about the applied job.
- `Database Schema.pdf`: Contains the prepared database star schema.

### SQL Analysis.sql

Details about the data analysis performed using SQL queries.

### Dashboard - Tableau.twbx

Tableau dashboard created for visualizing the analyzed data.

### Job analytics- Project presentation.pptx

Presentation slides providing an overview of the job analytics project.

Please refer to the specific files and folders for more detailed information on their content and usage.

## About Project

### Problem Statement

Scrape data from the professional networking platform Linkedin using Python library called Beautifulsoup (or similar) and collate information in the specific format and make 3 tables using the data. For analysis purposes, extract the sections highlighted in red in the screenshot below.

![project img 1](https://github.com/JiteshMore/LinkedIn_Job_Analytics/assets/132353761/f11b5f07-8fe9-410c-92ff-ec39fe427e38)

### Methodology

The project follows the following methodology:

1. **Data Collection:**
   - Utilize web scraping techniques with a Python library such as Beautiful Soup or a similar library to extract data from the LinkedIn platform. Specifically, scrape the sections highlighted in red in the provided screenshot to gather the required information for analysis.

2. **Data Cleaning and Preprocessing:**
   - Perform data cleaning tasks to ensure the extracted data is accurate and consistent. Handle missing values, remove duplicates, and format the data appropriately for further analysis.

3. **Exploratory Data Analysis (EDA):**
   - Conduct exploratory data analysis on the collected data. Generate descriptive statistics, visualize distributions, and explore relationships between variables. Identify any patterns or trends that may be relevant to the analysis.

4. **Data Transformation and Formatting:**
   - Prepare the data for analysis by transforming it into a specific format suitable for the desired analysis. This may involve reshaping the data, aggregating it, or applying other necessary transformations.

5. **Data Analysis:**
   - Apply appropriate analytical techniques to derive insights from the data. This may include statistical analysis, data mining, or machine learning algorithms depending on the project requirements. Perform the analysis with a clear objective in mind, such as identifying key trends, patterns, or correlations.

6. **Data Visualization with Tableau:**
   - Utilize Tableau, a powerful data visualization tool, to create interactive and visually appealing visualizations. Present the analyzed data through charts, graphs, and dashboards to effectively communicate the findings.

7. **Data Organization in Tables:**
   - Organize the extracted data into three different tables based on their relationships. Explain the relationships and connections between these tables in a database schema.

8. **Summary and Conclusions:**
   - Summarize the results of the data analysis and draw meaningful conclusions based on the insights gained. Highlight the key findings, implications, and any actionable recommendations that arise from the analysis.

9. **Documentation and Presentation:**
   - Prepare comprehensive documentation in the form of a PowerPoint presentation (PPT). Include details about the project objectives, methodology, data sources, data analysis techniques used, visualizations, and key findings. Use the presentation to effectively present the project's findings and insights.

By following this methodology, the project aims to extract, clean, analyze, and visualize the relevant data from LinkedIn. The use of Tableau and the organization of data into tables provide a structured and visually appealing representation of the insights gained from the analysis. The documentation prepared in the form of a PPT presentation ensures clear communication of the project's objectives, methodology, and findings.

## Database Information

### Sample Dataset

The scraped data obtained from the website is in the following format:

![project img 2](https://github.com/JiteshMore/LinkedIn_Job_Analytics/assets/132353761/5a33cd8e-c29f-4461-b70f-e94eaafbdf60)

### Schema

After scraping the data, it was cleaned and separated into three different tables: company, jobs, and details. Below is the star schema representing the relationship between these tables:

![project img 3](https://github.com/JiteshMore/LinkedIn_Job_Analytics/assets/132353761/d9fb434a-d529-4e8c-a18d-6191061632a5)

## Insights

1. **Job Market Analysis:**
   - The most job offering domains are data analyst (20.36%) and developer (20%) compared to other domains.

![project img 4](https://github.com/JiteshMore/LinkedIn_Job_Analytics/assets/132353761/f817caca-31bb-4b22-846c-fae6a8f49fde)


2. **Top Hiring Companies:**
   - Based on the dataset, Uplers, Southerland, and Infosys are the companies with the highest number of job postings.

3. **Applicant Insights:**
   - Some jobs have a high number of applicants, indicating strong competition, while others have relatively fewer applicants, suggesting lower competition and potentially higher chances of securing the job.

![project img 5](https://github.com/JiteshMore/LinkedIn_Job_Analytics/assets/132353761/17623646-4d63-41bd-aeb7-794c3808041c)


4. **Geographical Job Distribution:**
   - The majority of job opportunities are concentrated in states like Karnataka, Rajasthan, Tamil Nadu, and Maharashtra.

![project img 6](https://github.com/JiteshMore/LinkedIn_Job_Analytics/assets/132353761/f76671bd-03ad-4083-a02f-78339daa7819)


5. **Thriving Job Market in Bangalore:**
   - Within Bangalore, more companies are available across different fields of job.


6. **Industry Analysis:**
   - The IT Services and IT Consulting industry has the most job postings.


![project img 7](https://github.com/JiteshMore/LinkedIn_Job_Analytics/assets/132353761/7e4ca1df-e83b-4008-bf4a-d872eeb4870d)


## Challenges

The ultimate challenge was figuring out how to scrape data from the website. On the first day, we conducted research on web scraping techniques. After exploring various options, we determined that Selenium would best fit our requirements.

## Learning

Throughout the project, we gained knowledge about Selenium through various resources. 

Reference links:

- [YouTube Tutorial 1](https://www.youtube.com/watch?v=lTypMlVBFM4)

- [YouTube Tutorial 2](https://www.youtube.com/watch?v=Xjv1sY630Uc)

We also referred to the official Selenium documentation for detailed information.

## Dashboard

Tableau Dashboard: [Linkdean Job Analysis Dashboard](https://public.tableau.com/app/profile/prashantmane572/viz/Linkdean_Jobanalysis/JobAnalysis?publish=yes)

![project img 8](https://github.com/JiteshMore/LinkedIn_Job_Analytics/assets/132353761/223821f3-4811-471e-b96c-7d3badb0cf19)

## Conclusion

In this project, we successfully scraped job data from LinkedIn, cleaned and analyzed the data, and visualized the findings. Here are the key takeaways:

- The job market analysis revealed that the most in-demand domains are data analyst and developer.
- Top hiring companies, including Uplers, Southerland, and Infosys, had a significant number of job postings.
- Job opportunities were concentrated in states like Karnataka, Rajasthan, Tamil Nadu, and Maharashtra.
- Bangalore emerged as a thriving job market, offering a diverse range of job opportunities across different fields.
- The IT Services and IT Consulting industry showcased the highest number of job postings.
- Job involvement types varied from full-time to part-time and contract, and job levels spanned from entry-level to senior management.
- Applicant insights highlighted varying levels of competition, with some jobs receiving a high number of applicants and others having relatively lower competition.
- The Tableau dashboard here provides a detailed visualization of the analyzed data.

By following this methodology and utilizing Tableau for visualization, we gained valuable insights into the job market, enabling us to understand trends, identify top companies, explore geographical job distributions, and analyze job involvement and applicant insights.

**Note: Demo Project for Study Purposes**
This project is intended as a demonstration for educational purposes only. It serves as an example of how to scrape data from LinkedIn, clean and analyze the data, and visualize the findings using Tableau. The data used in this project is simulated or anonymized and does not reflect real-world data.

Please note that approximately 300 job listings were scraped from LinkedIn for the purpose of this demo. The data may not represent the actual job market conditions or trends.

Feel free to explore the code, methodologies, and visualizations presented here to enhance your understanding of web scraping, data analysis, and data visualization techniques. However, please refrain from using this project or its code for any commercial or production purposes without proper authorization.

If you have any questions or suggestions, please reach out to the project maintainers.

**Happy studying and learning!**
