# API Integration and Web Scraping Project

## Part 1: iPstack and MongoDB

### Database Programming
1. Write a Python program to:
   - Connect to my local MongoDB instance.
   - Created a database named "iPstack".
   - Insert the document {"ip": "192.168.1.1", "city": "Davis", "zip": "95616"} into a collection called "ip_addresses" within the "iPstack" database.

### Explored iPstack API
1. Visit [ipstack.com](https://ipstack.com/) and requested a free API key.
2. Read the API documentation to understand how to specify output format and response fields.

### API Call Program
1. Developed a Python program that makes API calls to iPstack for five different IP addresses.
2. Displayed the results on the screen.

### JSON Parsing
1. Converted the JSON strings obtained from API responses into Python objects.
2. Wrote code to iterate through the responses and print the "city" and "zip" fields to the screen.

### Data Storage Enhancement
1. Modified the code to insert all five "ip", "city", and "zip" records into the "ip_addresses" collection.

## Part 2: eBay + Selenium

### Automated Browser to Access eBay
1. Used Selenium in Python to launch a browser and navigate to [eBay](https://www.ebay.com/).

### Search for Items on eBay
1. Utilized Selenium to perform a search for "Cell Phones" on eBay.

### Applied Filters
1. Used Selenium to apply filters such as network, brand, screen size, storage capacity, lock status, and condition to the search results.
2. Saved the filtered results page as "unlocked-lg-128gb-used.html" on my local filesystem.

### Parse and Analyze Data
1. Opened and parsed the saved HTML file using BeautifulSoup (Python).

### Extract and Print Information
1. For each item listed on the parsed page, extracted and printed details such as title, seller, seller rating, price, shipping information, return information, and number of bids.

## Conclusion

This project demonstrates proficiency in API integration, web scraping, and database programming using Python. It provided me with practical experience in accessing external APIs, parsing web data, and storing information in a database. All code is well-commented to explain functionality and design decisions.
