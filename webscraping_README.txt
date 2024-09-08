This project collection focuses on scraping horse race data from Swiftbet, a website that utilizes dynamic JavaScript content. 
Initially, the scraping process was automated using Selenium and BeautifulSoup (bs4) to handle page navigation and content loading.
However, after discovering the website's API endpoints, I optimized the approach by using cURL commands to directly fetch data, making the process more robust and efficient.

Project Overview

Task 1 & Task 2: Web Scraping with Selenium and BeautifulSoup
              1. Scrape today's and tomorrow's horse race data. The scraped data is structured into a DataFrame and exported to a CSV file.
              2. Randomly select a horse race scheduled for tomorrow. Scrape the relevant data, including horse names and odds, and export it to a CSV file.


Task 3: API Scraping with cURL
              3. Optimize the scraping process by accessing the Swiftbet API directly using a cURL command. Scrape tomorrow's horse race data, construct a DataFrame, and export it to a CSV file.