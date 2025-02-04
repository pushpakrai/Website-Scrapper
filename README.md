# AmbitionBox Scraper  

### Description  
A Python-based web scraper designed to extract company details, ratings, reviews, types, and locations from [AmbitionBox](https://www.ambitionbox.com). This tool utilizes **BeautifulSoup** for parsing web content and **pandas** for data structuring, enabling efficient data analysis.  

---

### Features  
- Extracts company names, ratings, reviews, types, and locations.  
- Parses "Highly Rated For" and "Critically Rated For" sections.  
- Saves data as a structured pandas DataFrame.  
- Handles missing data gracefully to avoid errors.  

---

### Requirements  
- Python 3.x  
- Required libraries:  
  ```bash
  pip install requests beautifulsoup4 pandas
