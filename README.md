📈 Web Scraping and Data Visualization: U.S. Largest Companies by Revenue
This project uses Python to scrape data from Wikipedia and visualize insights about the largest companies in the United States by revenue.

🧾 Description
The script performs the following:

Scrapes an HTML table from a Wikipedia page

Extracts relevant company data (name, industry, employees, revenue, growth, etc.)

Saves the data to a CSV file

Reads the CSV and creates visualizations using Seaborn and Matplotlib

🧰 Technologies Used
Library	Purpose
requests	To send HTTP requests to the website
BeautifulSoup	For parsing and extracting HTML elements
pandas	For data manipulation and CSV export
matplotlib	For data visualization (basic plots)
seaborn	For enhanced statistical plots

📊 Visualizations
Scatter Plot: Companies vs. Number of Employees

Bar Plot: Industry vs. Rank

Pie Chart: Distribution of Companies by Industry

Box Plot: Revenue Growth Distribution by Industry

🗂 Output Example
CSV File Path:

bash
Copy code
D:/intern/moviedata.csv
You can change this path in the script to suit your local machine.

▶️ How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/us-companies-webscraper.git
cd us-companies-webscraper
Install dependencies:

bash
Copy code
pip install requests beautifulsoup4 pandas matplotlib seaborn
Run the Jupyter Notebook or Python script:

bash
Copy code
jupyter notebook Project.ipynb
📌 Notes
Make sure you have an internet connection while scraping.

The script uses the first <table> element found on the page — ensure the Wikipedia structure hasn’t changed.

Adjust df.to_csv() path as per your system directory.

🛡️ Disclaimer
This is an educational project. Wikipedia content is licensed under CC BY-SA 3.0.

📬 Contact
For feedback, feel free to raise an issue or reach out via GitHub.
