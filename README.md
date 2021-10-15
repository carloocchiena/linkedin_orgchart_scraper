# linkedin_orgchart_scraper
A Python automation that allows to extract company names and roles from an input compan, using Selenium and BSoup.

Even if the current script is doing very little, it opens many ways to increase its functionality such as getting emails, persona urls, numbers of people in the company, doing multiple searches and so on. 

### Release notes:
15/10/2021 removed dependencies from lxml module that may cause trouble in conda venv and switched to built-in html.parser<br>
15/10/2021 added "company_list.py" to scrape thru a list of given companies. This is tested and working with latest class and div tags
15/10/2021 noticed that main.py is not working anymore since the class tags in Linkedin changed. This is quite frequent and atm i have no reason to maintain this repo in real time. But in the case I'll be glad to help if someone may need assistance.

