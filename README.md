## Femicide in Turkey Data Scraper
This small ETL project scrapes and transforms data on femicide in Turkey, loading it into a MySQL database for structured analysis. Using Python, BeautifulSoup, and SQLAlchemy, the pipeline extracts data from a web source called [Anıt Sayaç](https://anitsayac.com/) using Python and BeautifulSoup, transformed as needed, and saved in a MySQL database with SQLAlchemy for efficient data handling.

### Requirements
Python (>=3.7)  
MySQL  
Jupyter Notebook

#### Install dependencies with:
```
pip install -r requirements.txt
```

### Usage
**Set up the MySQL database:** Create a MySQL database and update connection credentials in [db-config.json](https://github.com/bdemir00/web-scraping-turkey-femicide/blob/main/db_config.json).  
**Run the Notebook:** Open and run the .ipynb file to execute the data pipeline.

### Acknowledgments
The scraped data in this project is in Turkish and intended for research and educational purposes, providing a foundation for analysis on femicide cases in Turkey.

