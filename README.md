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

## 📋 All Commands — California (50)

```bash
python ai_maps_scraper.py --keyword "dentists" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "dentists" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "dentists" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "dentists" --location "Sacramento California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "dentists" --location "Fresno California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "Sacramento California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "Fresno California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "Sacramento California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "Fresno California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "Sacramento California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "Fresno California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "Sacramento California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "San Jose California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "Oakland California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "Long Beach California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "Riverside California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "Bakersfield California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "San Jose California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "Anaheim California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "gyms fitness centers" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "gyms fitness centers" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "gyms fitness centers" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "insurance agents" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "insurance agents" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "pest control" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "pest control" --location "San Diego California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "landscaping" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "landscaping" --location "San Francisco California" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "financial advisors" --location "Los Angeles California" --max 120 --output "D:\all_leads.xlsx"
```

---

## 🇺🇸 All Commands — USA Excluding California (50)

```bash
python ai_maps_scraper.py --keyword "dentists" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "dentists" --location "Dallas Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "dentists" --location "Phoenix Arizona" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "dentists" --location "Chicago Illinois" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "dentists" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "Dallas Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "Phoenix Arizona" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "Chicago Illinois" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "plumbers" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "Dallas Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "Phoenix Arizona" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "Chicago Illinois" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "HVAC" --location "Miami Florida" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "Dallas Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "Phoenix Arizona" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "Chicago Illinois" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "roofing contractors" --location "Miami Florida" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "Dallas Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "Phoenix Arizona" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "real estate agents" --location "Miami Florida" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "Dallas Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "Phoenix Arizona" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "Chicago Illinois" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "electricians" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "Chicago Illinois" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "Miami Florida" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "lawyers" --location "Phoenix Arizona" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "Dallas Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "Chicago Illinois" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "auto repair shops" --location "Miami Florida" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "gyms fitness centers" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "gyms fitness centers" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "gyms fitness centers" --location "Chicago Illinois" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "pest control" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "pest control" --location "Miami Florida" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "landscaping" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "landscaping" --location "Dallas Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "insurance agents" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "insurance agents" --location "Houston Texas" --max 120 --output "D:\all_leads.xlsx"
python ai_maps_scraper.py --keyword "financial advisors" --location "New York City" --max 120 --output "D:\all_leads.xlsx"
```

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
