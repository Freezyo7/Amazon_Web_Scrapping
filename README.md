🛍️ Amazon Laptop Web Scraper
This project is a Python-based web scraper built using BeautifulSoup, Requests, and time.sleep() to extract detailed information about laptops listed on Amazon India.

📌 Project Description
The goal of this project is to collect structured product data from Amazon for laptops. This includes extracting useful information like title, price, MRP, discount, rating, and availability. The extracted data is saved into a CSV file for further analysis, visualization, or integration into data pipelines.

✅ Features
Extracts:

🖥️ Laptop Title

💸 Price

📉 Discount Percentage

🏷️ MRP (Original Price)

⭐ Ratings

📦 Availability Status

Uses requests to fetch HTML content.

Parses data using BeautifulSoup.

Implements delay with time.sleep() to avoid rapid requests and reduce the chance of being blocked.

Saves data in CSV format for easy data processing.
