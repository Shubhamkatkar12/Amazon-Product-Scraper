# Amazon-Product-Scraper

📌 Project Objective
The objective of this project is to develop a web scraping tool that extracts product details from Amazon, including product titles, prices, ratings, reviews, and availability. The tool is designed to:

Automate data collection from Amazon's product pages.
Track product prices and availability over time.
Provide insights for price comparison, trend analysis, and competitive research.
Store extracted data in a structured format (CSV) for further analysis.


 Project Summary
The Amazon Product Scraper is a Python-based web scraping tool that uses requests and BeautifulSoup to collect product information from Amazon India. The scraper follows these steps:

Send an HTTP request to an Amazon product category page.
Parse the HTML content using BeautifulSoup.
Extract product links from the category page.
Visit individual product pages to collect details such as:
Product title
Price (including deal prices)
Ratings
Review count
Availability status
Rotate User-Agents and introduce delays to avoid detection.
Store the extracted data in a structured CSV file (amazon_data.csv).


📌 Conclusion
The Amazon Product Scraper successfully extracts key product details from Amazon automatically. It demonstrates:
✅ Effective web scraping techniques using Python.
✅ Data collection automation for e-commerce analysis.
✅ Preventive measures against website blocking (User-Agent rotation, delays).
✅ Efficient data storage for further business insights.
