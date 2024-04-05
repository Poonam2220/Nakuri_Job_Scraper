# Naukri Job Scraper
This is a Python script for scraping job details from Naukri.com using Selenium, specifically targeting job listings in the Delhi-NCR region.

# Table of Contents
- Introduction
- Features
- Requirements
- Installation
- Usage
- Configuration
- Credits
- Contributing
- License

# Introduction
Naukri Job Scraper is a tool built with Python and Selenium to extract job listings from Naukri.com. It automates the process of gathering job details such as job title, company name, experience required, salary, location, as well as additional details like openings, applicants, education requirements, employment type, and industry type..

# Features
- Scrape job listings from Naukri.com in the Delhi-NCR region.
- Extracts basic job information as well as additional details from job listings
- Saves data to a CSV file for further analysis
  
# Requirements
To use this script, you need:

- Python 3.x
- Selenium
- Chrome WebDriver
- YAML
  
# Installation
1. Clone the repository:
git clone https://github.com/Poonam2220/Nakuri_Job_Scraper.git

2. Install the required Python packages:
pip install -r requirements.txt

# Usage
1. Modify the "config.yml" file with your desired settings.
2. Run the script:
python main.py

# Configuration
You can customize the scraper using the "config.yml" file. Here's a brief explanation of each configuration option:

- 'scraping':
  * url: The URL of the Naukri search page you want to scrape.
   * job_count: The number of job listings you want to scrape.
- 'selenium':
  * chromedriver_path: The path to the Chrome WebDriver executable.
 
 ## Credits
 The structure of the scraping code was adapted from @ raghwendraranjeet (https://github.com/raghwendraranjeet/Naukri_Data)

 
# Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvement, please feel free to open an issue or submit a pull request.
  
# License
This project is licensed under the MIT License - see the LICENSE file for details.
