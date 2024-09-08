# Amazon Product Scraper ETL Pipeline

## Overview

This project demonstrates my expertise in data engineering by building a complete ETL (Extract, Transform, Load) pipeline using Python and Jupyter Notebook. The pipeline scrapes product information from Amazon, processes the data, and exports it into a structured format for analysis. The pipeline showcases skills in web scraping, data extraction, transformation, and loading (ETL), focusing on high-quality, clean data.

### Key Features:
- **Data Extraction**: Scrapes Amazon product details, including titles, prices, ratings, reviews, and availability.
- **Data Transformation**: Cleans and structures the scraped data for consistency and accuracy.
- **Data Loading**: Saves the data into a CSV file for further analysis or reporting.

## Skills Highlighted

- **Data Scraping & Web Automation**: Utilizing Python libraries like `requests` and `BeautifulSoup` to extract data from web pages.
- **Data Engineering**: Implementing the ETL pipeline to process raw data and transform it into usable formats.
- **Data Cleaning**: Handling missing data and ensuring clean, structured output using Pandas.
- **Web Scraping Best Practices**: Implementing user-agent headers and other techniques to comply with web scraping standards.
- **Data Persistence**: Storing transformed data efficiently into CSV format for further use or analysis.

## Tools & Technologies

- **Python**: Core language for writing the ETL pipeline.
- **Libraries Used**:
  - `requests`: To send HTTP requests and retrieve HTML content from Amazon.
  - `BeautifulSoup`: To parse and extract relevant data from HTML.
  - `Pandas`: To transform and manipulate the data.
  - `NumPy`: For handling missing data and performing data replacements.
- **Jupyter Notebook**: For running the Python scripts and creating an interactive development environment.
- **CSV**: For storing the final cleaned data.

## Project Setup

### Prerequisites:
- Python 3.x installed
- Necessary libraries: `requests`, `beautifulsoup4`, `pandas`, `numpy`

Install the dependencies:

```bash
pip install requests beautifulsoup4 pandas numpy
```
### Running the ETL Pipeline
Clone the repository:

```bash
git clone https://github.com/your-repo/amazon-product-scraper.git
```
Open the Jupyter Notebook:

```bash
jupyter notebook amazon_scraper.ipynb
```
Run the cells to:

Extract product data from Amazon.
Transform and clean the data.
Load the cleaned data into a CSV file.
Output: The final dataset will be saved as amazon_data.csv.

### Future Enhancements
Real-time Data Fetching: Implement real-time data scraping for updated product information.
Data Analytics: Perform trend analysis on product ratings and prices using data visualization techniques.
Database Integration: Store the data in a database (PostgreSQL, MongoDB) for better scalability.

### Conclusion
This ETL pipeline highlights my ability to create robust data pipelines, extract web data, transform it into actionable insights, and load it into a structured format. My data engineering skills can benefit companies looking to leverage web data for business insights and decision-making.
