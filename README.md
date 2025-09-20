# 🏠 Rent-Calculator--Bubble.io-App

This project is a **proof-of-concept Rent Calculator** built to demonstrate both **data analysis** and **no-code app development**.

🔹 **Why?**  
While exploring properties myself, I realised it was difficult to quickly estimate rental averages and yields across suburbs. At the same time, my job search required experience in no-code tools, so I combined the two challenges into a project.

🔹 **What I built**  
1. **Data scraping (Python)**  
   - Used `requests` + `BeautifulSoup` for static pages.  
   - Used `Playwright` for dynamic/JS-rendered pages.  
   - Parsed suburb, property type, bedrooms, rent, etc.  

2. **Data cleaning & analysis (pandas)**  
   - Normalised weekly/monthly rent values.  
   - De-duplicated listings by ID + address.  
   - Calculated average rent and yield per suburb/property type.  

3. **No-code app (Bubble.io)**  
   - Built a simple MVP app: [👉 Live Demo](https://rent-calculator-34476.bubbleapps.io/)  
   - Dropdown filters for suburb/property/bedrooms.  
   - Returns average rent or yield instantly.  

---

## 📂 Repo Structure
- `scraping/` → Python scripts to scrape listings.  
- `analysis/` → Notebook for cleaning + calculations.  
- `data/` → Example dataset (CSV).  
- `app_link.txt` → Link to Bubble MVP.  

---

## 🚀 How to run the scraper

**Requirements**: Python 3.9+, pip install:
```bash
pip install requests beautifulsoup4 pandas playwright
playwright install
