# -Magicbricks-Property-Scraper
This is a Python web scraping application developed to extract property listings from Magicbricks. The project utilizes the BeautifulSoup library for parsing HTML and extracting the required data. The extracted data is then processed and cleaned using Pandas, enabling further analysis and visualization.

Libraries Used

requests: Used for sending HTTP requests to the Magicbricks website and retrieving the HTML content of the property listings pages.

pandas: Employed for data cleaning, processing, and organizing the extracted property data into a structured format.

BeautifulSoup (bs4): Utilized for parsing the HTML content and extracting specific information from the Magicbricks property listings.

Functionality
The Magicbricks Property Scraper performs the following steps:

Sends an HTTP request to the Magicbricks website to retrieve the HTML content of the property listings page.
Uses BeautifulSoup to parse the HTML content and extract the relevant property information such as the flat name, flat price, owner name, and square footage.
Cleans and organizes the extracted data using Pandas, ensuring consistency and uniformity.
Stores the extracted data in a pandas DataFrame for further analysis and visualization.

Usage:

To use this application, make sure you have the following libraries installed:

requests

pandas

BeautifulSoup (bs4)

Simply run the Python script and the application will scrape the Magicbricks property listings, extract the desired information, and store it in a pandas DataFrame.

