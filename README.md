# Naukri Job Scraper
This is a Python script for scraping job details from Naukri.com using Selenium.

# Table of Contents
- Introduction
- Features
- Requirements
- Installation
- Usage
- Configuration
- License

# Introduction
Naukri Job Scraper is a tool built with Python and Selenium to extract job listings from Naukri.com. It automates the process of gathering job details such as job title, company name, experience required, salary, location, and more.

# Features
- Scrapes job details from Naukri.com
- Extracts basic job information as well as additional details from job listings
- Saves data to a CSV file for further analysis
- 
# Requirements
To use this script, you need:

- Python 3.x
- Selenium
- Chrome WebDriver
- YAML
  
# Installation
1. Clone the repository:
git clone https://github.com/yourusername/naukri-job-scraper.git

2. Install the required Python packages:
pip install -r requirements.txt

# Usage
1. Modify the "config.yml" file with your desired settings.
2. Run the script:
python main.py

# Configuration
You can customize the scraper using the config.yml file. Here's a brief explanation of each configuration option:

- scraping:
 - url: The URL of the Naukri search page you want to scrape.
 - job_count: The number of job listings you want to scrape.
-selenium:
  - chromedriver_path: The path to the Chrome WebDriver executable.
  
# License
This project is licensed under the MIT License - see the LICENSE file for details.
