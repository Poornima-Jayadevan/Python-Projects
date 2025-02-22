# Books Scraper

## 📌 Project Overview
This is a **Scrapy-based web scraper** that extracts book titles, prices, and URLs from [Books to Scrape](https://books.toscrape.com/). The extracted data is stored in a JSON file for further analysis.

---

## 🛠️ Installation
### 1️⃣ Install Python (if not installed)
Ensure you have **Python 3.6+** installed. Check with:

```sh
python --version
```

If not installed, download it from [python.org](https://www.python.org/downloads/).

### 2️⃣ Install Scrapy
```sh
pip install scrapy
```

### 3️⃣ Clone or Download the Repository
```sh
git clone https://github.com/your-username/books_scraper.git
cd books_scraper
```
---

### View the Output
Open `books.json` to see the extracted data:
```json
[
    {
        "title": "A Light in the Attic",
        "price": "£51.77",
        "url": "https://books.toscrape.com/catalogue/a-light-in-the-attic_1000/index.html"
    }
]
```

---

## 🛠️ Troubleshooting
### ❌ "Spider Not Found" Error
- Make sure you are inside the Scrapy project directory before running the command.
- Check that `books_spider.py` exists in `books_scraper/spiders/`.

### ❌ "scrapy command not found"
- Ensure Scrapy is installed correctly using `pip install scrapy`.
- Try running with Python:
  ```sh
  python -m scrapy crawl books -o books.json
  ```

---

## 🌟 Acknowledgments
- [Scrapy Documentation](https://docs.scrapy.org/)
- [Books to Scrape](https://books.toscrape.com/) for providing sample data.

---

