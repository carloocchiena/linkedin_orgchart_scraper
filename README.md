# linkedin_orgchart_scraper
A Python automation that allows to extract company names and roles from an input compan, using Selenium and BSoup.

Even if the current script is doing very little, it opens many ways to increase its functionality such as getting emails, persona urls, numbers of people in the company, doing multiple searches and so on. 

### Release notes:
15/10/2021 removed dependencies from lxml module that may cause trouble in conda venv and switched to built-in html.parser
15/10/2021 added "company_list_txt.py" to scrape thru a list of given companies
