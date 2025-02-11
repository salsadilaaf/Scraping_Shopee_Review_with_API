# Scraping Shopee Review 
Shopee Review Scrape with API

This project is a web scraper designed to automatically collect product reviews from Shopee using Python. By providing a Shopee product URL, the script extracts the Shop ID and Item ID, then accesses Shopee's API to retrieve user review data, including username, rating, comments, and review date. The scraped data is then saved as an Excel (.xlsx) file for further analysis.

Key Features:
✅ Automatic extraction of Shop ID and Item ID from the product URL
✅ Scrapes product reviews from Shopee's API with built-in error handling
✅ Stores data in Excel (.xlsx) format for easy analysis
✅ Automatic delay mechanism to avoid getting blocked by Shopee

How to Use:
Replace the product URL in the url variable with the Shopee product URL you want to scrape
Run the script using Python
The review data will be automatically saved as shopee_reviews.xlsx
