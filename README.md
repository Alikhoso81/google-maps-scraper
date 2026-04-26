# 🗺️ Google Maps Lead Scraper

A powerful, free Google Maps scraper that extracts business leads including **phone numbers, websites, addresses, ratings** and saves everything into a single growing Excel file.

> ✅ No API key needed  
> ✅ Appends data — never loses old leads  
> ✅ Works for any keyword + any location worldwide  
> ✅ Exports clean Excel file ready for outreach  

---

## 📸 What It Does

- Opens Google Maps automatically in a real browser
- Scrolls and collects all business listings
- Extracts: Business Name, Phone, Website, Address, City, State, Rating, Reviews, Hours
- Saves everything to one Excel file — each new run **adds** to the file

---

## ⚙️ Setup (Run Once)

**1. Install Python**
Download from: https://python.org

**2. Install dependencies**
```bash
pip install playwright openpyxl
playwright install chromium
```

**3. Clone this repo**
```bash
git clone https://github.com/YOUR_USERNAME/google-maps-scraper.git
cd google-maps-scraper
```

---

## 🚀 Usage

```bash
python ai_maps_scraper.py --keyword "dentists" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
```

| Argument | Description | Example |
|---|---|---|
| `--keyword` | Business type to search | `"dentists"` |
| `--location` | City and state | `"Houston Texas"` |
| `--max` | Max results per run (Google caps at ~120) | `120` |
| `--output` | Excel file to save to (always use same file!) | `"D:\all_leads.xlsx"` |

---

## 📊 Output Columns

| Column | Description |
|---|---|
| Business Name | Name of the business |
| Phone | Phone number |
| Website | Business website |
| Google Maps URL | Direct Maps link |
| Address | Full address |
| City | City |
| State | State |
| Business Type | Keyword used |
| Rating | Star rating |
| Total Reviews | Number of reviews |
| Hours | Opening hours |
| Owner Name | Fill manually |
| Owner Email | Fill manually |
| Scraped Date | Auto-filled |

---

---

## 💡 Tips

- Always use `--output "D:\all_leads.xlsx"` to keep all data in one file
- Google caps results at ~120 per search — this is normal
- Run commands one by one, not all at once
- If Google blocks you, wait 30 minutes and continue

---

## 📁 Project Structure

```
google-maps-scraper/
│
├── ai_maps_scraper.py     # Main scraper script
├── README.md              # This file
└── requirements.txt       # Python dependencies
```

---

## 📦 Requirements

```
playwright
openpyxl
```

Install with:
```bash
pip install -r requirements.txt
playwright install chromium
```

---

## ⚠️ Disclaimer

This tool is for educational purposes. Use responsibly and respect Google's Terms of Service. Do not run too many searches in a short time.

---

## 🙋 Author

Built for local business lead generation.
Feel free to fork, star ⭐ and contribute!
