# Scraping Script: Indeed Job Salaries + Key Words
Jupyter Notebook that performs a scraping of Indeed job posts for user-inputted key words.

Requirements:
  - Selenium is required;  can be installed using  pip install selenium
  - Selenium Webdriver (this notebook uses Chromedriver) required: can be downloaded from https://chromedriver.chromium.org/downloads
  Note: Webdriver must match the version of the browser installed on system

Notebook will output a csv file with:
  - Job name
  - Company
  - Search Location (not precise job location)
  - Job location average salary (-1 if missing)
  - Pay Type ('unlisted' if missing)
  - Minimum Salary
  - Maximum Salary
  - A column for each skill keyword inputted: 0 for missing and 1 for present in job description
 
