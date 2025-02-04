# 🚀 Web Scraper  

## 📌 Description  
AmbitionBox Scraper is a **Python-based web scraper** designed to extract **company details, ratings, reviews, job types, and locations** from [AmbitionBox](https://www.ambitionbox.com). It leverages **BeautifulSoup** for HTML parsing and **pandas** for data structuring, making it easy to analyze and visualize the extracted data.  

---

## ✨ Features  
✅ Extracts **company names, ratings, reviews, job types, and locations**  
✅ Scrapes **Highly Rated For** and **Critically Rated For** sections  
✅ Stores data in a **structured pandas DataFrame**  
✅ Handles missing values gracefully to prevent errors  
✅ Saves results in **Excel (.xlsx) format** for easy access  

---

## 🔧 Installation  
Make sure you have **Python 3.x** installed, then install the required dependencies:  

```bash
pip install requests beautifulsoup4 pandas openpyxl
```

---

## 🚀 Usage  
Run the script to start scraping:  

```bash
python ambitionbox_scraper.py
```

You can also run it inside **Jupyter Notebook**:  

```python
from ambitionbox_scraper import scrape_data
scrape_data()
```

The extracted data will be saved as an Excel file (`data_file.xlsx`) for further analysis.  

---

## 📂 Project Structure  
```
📂 AmbitionBox-Scraper  
 ├── 📜 ambitionbox_scraper.ipynb   # Jupyter Notebook with scraping logic  
 ├── 📜 ambitionbox_scraper.py      # Python script for standalone execution  
 ├── 📂 data/                        # Folder to store extracted data  
 │   ├── data_file.xlsx             # Output file with scraped data  
 ├── 📜 README.md                    # Project documentation  
```

---

## 📊 Output Example  
| Company Name       | Rating | Reviews | Job Type | Location |
|--------------------|--------|---------|----------|----------|
| XYZ Corp          | 4.2    | 1,230   | IT       | Mumbai   |
| ABC Ltd           | 3.8    | 890     | Finance  | Bangalore |
| Tech Innovators   | 4.5    | 2,500   | Software | Pune     |

---

## 🛠 Dependencies  
- **requests** → To fetch web pages  
- **BeautifulSoup4** → For HTML parsing  
- **pandas** → To structure and analyze data  
- **openpyxl** → To save data in Excel format  

---

## ⚠️ Disclaimer  
This project is for **educational purposes only**. Scraping websites without permission may violate their terms of service. Always check the website's **robots.txt** before scraping.  

---

## 📜 License  
This project is licensed under the **MIT License**.  
