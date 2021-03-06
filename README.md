# Python-LinkedIn-Information-Scraper

LinkedIn Scraper using Python 3.7.2

Useful for gathering data of a user from LinkedIn.

Given the URL of a LinkedIn profile, it gets the Name, Title, Education History, Project History, Employment History, Certifications, Project, Skills, Accomplishments and Volunteering History from the LinkedIn Profile.

## Libraries Used:

> BeautifulSoup

> selenium

> re

> json

> time

## Requirements:

> Python 3.x

> Pip

> chromedriver 



## Installation

### Clone
Clone this repo to your local machine using 
> git clone https://github.com/premnagdeo/Python-LinkedIn-Information-Scraper.git

### Chrome Web Driver
The Chrome Driver can be found here: https://chromedriver.chromium.org/downloads

### Setup
Install BeautifulSoup
```
pip install beautifulsoup4
```

Install Selenium
```
pip install selenium
```


## Usage

* Edit the 'config.txt' file and add your linkedin username and password
> This is required because linkedin requires a login before you can view a profile

* Edit the 'link' variable on line 41 and assign it the link to the profile that is to be scraped.
> link = 'https://www.linkedin.com/in/premnagdeo/'

* Run the Python Program
> python linkedin_scraper.py

* Output of the program is saved in .json file named 'scraped_data.json' which is created at runtime.
> [sample output](/output/scraped_data.json)
## Support

Reach out to me at:

- Gmail  <a href="http://premnagdeo@gmail.com" target="_blank">`premnagdeo@gmail.com`</a>
- LinkedIn  <a href="https://www.linkedin.com/in/premnagdeo/" target="_blank">`https://www.linkedin.com/in/premnagdeo/`</a>
