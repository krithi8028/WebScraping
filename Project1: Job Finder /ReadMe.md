# Job Finder

## Overview 
This Jupyter Notebook contains a Python script that scrapes job information from a website and filters out jobs based on user-specified skills. The extracted job details are stored in a single text file.


## How to use
1. Run each cell in the notebook sequentially.
2. When prompted, input skills you are not familiar with.


The script will scrape job information, filter out jobs based on the specified skills, and store the details in a file named `jobs_info.txt`.

## Dependencies
- [requests](https://docs.python-requests.org/en/master/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

## Notes
- Ensure you have the required Python libraries installed.
- The script will run indefinitely, waiting for 1 minute between each iteration.
