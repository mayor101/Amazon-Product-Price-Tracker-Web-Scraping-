# Amazon-Product-Price-Tracker-Web-Scraping-
This is a web scrapping project using Python. 
This project is an automated Amazon price tracker built with Python. It scrapes product information such as title and price from an Amazon product page, stores the data along with the collection date, and sends an email alert when the price drops below a specified threshold.

*Tools & Libraries
Python 
BeautifulSoup (bs4) – HTML parsing
Requests – Fetching webpage content
Pandas – Structuring and storing data
smtplib – Sending email alerts
Schedule / Time – Automating daily data collection

*Features
Scrapes product title and current price from Amazon
Automatically adds the date of data collection
Runs every 24 hours to check for price changes
Saves scraped data to a CSV file for ongoing price tracking
Sends an email notification when the price drops to $15 or below

*Use Case
This automation is useful for price monitoring, competitive analysis, or personal use cases such as tracking discounts for desired products.

*Future Improvements
Expand to monitor multiple product URLs
Integrate with a SQL database or Power BI for trend visualization
Deploy as a lightweight web app or scheduled cloud function
