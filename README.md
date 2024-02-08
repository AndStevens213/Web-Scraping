# Web-Scraping
# Web Scraping Table with BeautifulSoup

## Overview
This Python script demonstrates how to scrape a table from a webpage using the BeautifulSoup library and store the extracted data into a pandas DataFrame. The script assumes that the table is structured in HTML format and can be located using BeautifulSoup.

## Requirements
- Python 3.x
- BeautifulSoup (install via `pip install beautifulsoup4`)
- pandas (install via `pip install pandas`)
- requests (install via `pip install requests`)

## Usage
1. Clone or download the script to your local machine.
2. Make sure you have Python installed on your system.
3. Install required libraries if not already installed:
4. Replace `'URL_OF_THE_WEBPAGE'` in the script with the actual URL of the webpage containing the table you want to scrape.
5. Run the script:

## Script Explanation
- The script sends a GET request to the specified URL.
- It then parses the HTML content of the webpage using BeautifulSoup.
- The script locates the table within the HTML content.
- It iterates over the rows of the table, extracting the data into lists.
- Finally, it creates a pandas DataFrame from the extracted data and prints it.

## Author
Andrew Stevens
andrewdstevens213@gmail.com
asteve69@uncc.edu

Feel free to reach out with any questions or feedback!
