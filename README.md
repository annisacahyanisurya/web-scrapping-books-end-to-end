## 📚 Books to Scrape: Simple ETL Pipeline

###  Project Description
This project is a streamlined **ETL (Extract, Transform, Load)** pipeline designed to gather data from the [Books to Scrape](http://books.toscrape.com/) website. The primary goal is to demonstrate core competencies in **web scraping**, data manipulation using **Pandas**, and relational database management with **SQLite**.

### 🚀 Key Features
- **Extract**: Scrapes book titles and pricing data across multiple web pages using BeautifulSoup.
- **Transform**: 
  - Cleans price strings by removing currency symbols and converting to numerical format.
  - Implements **Price Categorization** (Budget, Mid-Range, Premium).
- **Load**: Saves the processed and structured data into a local SQLite database for further analysis.

### 🛠 Tech Stack
- **Language**: Python 3.x
- **Libraries**: Pandas, BeautifulSoup4, Requests, SQLAlchemy
- **Database**: SQLite

### 🏃‍♂️ How to Run
1. **Clone this repository**:
   ```bash
   git clone [https://github.com/annisacahyanisurya/web-scrapping-books-end-to-end.git](https://github.com/annisacahyanisurya/web-scrapping-books-end-to-end.git)
   ```

2. **Install Dependencies**
```bash
    pip install -r requirements.txt
```


