# surf-cdm

This Python program aims to scrape the DePaul University College of Computing and Digital Media (CDM) website to identify the 25 most common words. The crawling process is initiated from the main page http://cdm.depaul.edu, and it traverses through linked web pages until a maximum cap on the number of visited links (10,000) is reached.

Libraries Used:

urllib.request: For opening and reading URLs. <br />
urllib.parse: For joining and parsing URLs. <br />
html.parser: For HTML parsing. <br />
re: For regular expressions.

Please note that web scraping should be performed responsibly and in accordance with the website's terms of service.
