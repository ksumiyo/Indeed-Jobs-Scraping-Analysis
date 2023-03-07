# Scraping Script: Indeed Job Salaries + Key Words

Indeed_Job_Scrape_Script_Final: A Jupyter Notebook that performs a scraping of Indeed job posts, parameters inputted by user.
Indeed_Job_Scrape_Raw_02-09-2023_07-18-00.csv: An example output of the Indeed_Job_Scrape_Script_Final notebook.
Indeed_Job_Python_Tableau_Keyword_Cleaning&Wrangling-Final: A Jupyter notebook that analyzes the csv file included in this repository.

Indeed_Job_Scrape_Script_Final Notes:
  - Selenium is required;  can be installed using  pip install selenium
  - Selenium Webdriver (this notebook uses Chromedriver) required: can be downloaded from https://chromedriver.chromium.org/downloads
  Note: Webdriver must match the version of the browser installed on system
  - Outputs a csv file with the following header columns:
    - Job name
    - Company
    - Search Location (not precise job location)
    - Job location average salary (-1 if missing)
    - Pay Type ('unlisted' if missing)
    - Minimum Salary (-1 if missing)
    - Maximum Salary (-1 if missing)
    - A column for each skill keyword inputted: 0 for missing and 1 for present in job description

Indeed_Job_Python_Tableau_Keyword_Cleaning&Wrangling-Final Notes:
  - Analysis is based on the csv included in the repository
  - Analysis focuses on two keywords scraped in job posts: "Tableau" and "Python"
