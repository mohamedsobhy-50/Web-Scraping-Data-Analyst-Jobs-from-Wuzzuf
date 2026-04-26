# Web-Scraping-Data-Analyst-Jobs-from-Wuzzuf
In this project, I built a Python web scraping script to automatically extract Data Analyst job listings from Wuzzuf website and save them into a structured CSV file for further data analysis
🛠️ Tools & Libraries Used:
Python 🐍
Requests
BeautifulSoup (bs4)
CSV module
itertools (zip_longest)

⚙️ Project Steps:
1️⃣ Fetching the Web Page

Used the requests library to send a request and retrieve the HTML content of the job listing page.

2️⃣ Parsing the HTML

Used BeautifulSoup to parse and navigate the HTML structure.

3️⃣ Data Extraction

Extracted key job information such as:

Job Title
Company Name
Location
Required Skills
Job Links
4️⃣ Data Structuring

Organized all extracted data into separate lists and combined them using:

zip_longest
5️⃣ Saving Data

Exported the final structured dataset into a CSV file for further analysis.

📊 Project Importance:
Understanding Web Scraping fundamentals
Working with unstructured real-world data
Preparing datasets for analysis tools (Excel, Power BI, etc.)
A core skill for any Data Analyst

🚀 Outcome:

A clean CSV dataset containing real job postings ready for analysis.

