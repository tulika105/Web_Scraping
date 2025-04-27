# What is Web Scraping
Web scraping or web harvesting is a technique of extracting data from websites. The process involves fetching web pages, parsing their code, and saving the extracted information in a structured format for later use or analysis.
# Web Scraping with Python
- Inspecting the website's HTML to identify data elements.
- Using libraries like Requests to fetch pages and BeautifulSoup to parse and extract data.
- Exporting the results to a file or database.
# Things to remember while working on web scraping
- Request Headers: Some websites may block requests that look like they're from bots. You might need to add User-Agent headers to make your request look like it’s from a real browser.
- Handling Pagination: If you're scraping multiple pages, you must handle pagination and loop through different URLs. Use proxy servers.
- Respecting robots.txt: Always check the site's robots.txt file to ensure you can scrape it.
# Scraping Amazon's bestseller web pages of 50 books by authors, and their ratings
- Importing necessary packages(requests, BeautifulSoup, Pandas)
- Sending HTTP requests to get access to the HTML content of the web page to be scraped using the User-Agent Header.
- Parsing the HTML content using BeautifulSoup.
- Extracting all 50 author names and the book ratings.
- Saving the extracted data in a dataframe and exporting it to a CSV file.
# Scraping the Wikipedia web page of the top 50 unicorn companies, their names, the founder's name, valuation, and industry.
- Importing necessary packages(requests, BeautifulSoup, Pandas)
- Sending HTTP requests to get access to the HTML content of the web page to be scraped, and also checking the robots.txt file.
- Parsing the HTML content using BeautifulSoup.
- Extracting all the top 50 unicorn companies and their details.
- Saving the extracted data in a dataframe and exporting it to a CSV file.
## Analysing the dataset.
- 


