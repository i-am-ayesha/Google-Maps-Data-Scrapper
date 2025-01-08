#  Google Maps Scraper 🗺️
A simple and customizable scraper that uses Playwright to extract data from Google Maps. This project is designed for educational purposes and can be easily tailored to your needs.

📂 Check the Output:
You can export the scraped data to Excel and CSV formats. Take a look at the google_maps_data folder to see the final results.

## 🚀 How to Get Started:
1. Create a virtual environment and activate it (recommended for clean setup):

`virtualenv venv
source venv/bin/activate`

2. Install the required dependencies from requirements.txt:

`pip install -r requirements.txt`

3. Install Chromium for Playwright 


`playwright install chromium`

## ▶️ How to Run the Scraper:
### 1. Run a Single Search:
Use the following command to perform a single search:

`python3 main.py -s="<what & where to search>" -t=<how many results>`

Example:

`python3 main.py -s="dentist New York" -t=50`

This will search for dentists in New York and return 50 results.

### 2. Run Multiple Searches:
Add your search queries in input.txt. Each search should be written on a new line.

Example:

`dentist Boston
dentist New York
dentist Texas`

Then run:

`python3 main.py`

If you want to limit results for each search, use -t=<how many> and it will apply to all searches in the file.

### 💡 Pro Tips:
If you're trying to get more than 120 results, break down your search into smaller, more specific areas. Instead of doing broad searches like "United States dentist", make them more focused like:

`United States Boston dentist
United States New York dentist
United States Texas dentist`

This will give you more relevant results.

## 🛠️ Tech Stack:
1. Python 🐍
2. Playwright 🎭
3. Pandas 🐼
4. BeautifulSoup 🍲
   
## ✨ Key Features:
1. **Customizable:** Modify it to suit your exact search needs.
2. **Batch Queries:** Run multiple search queries at once with input.txt.
3. **Flexible Output:** Get your results in Excel or CSV.
4. **Precision Searches:** Refine searches for more detailed results.
