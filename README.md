# Turkish Super League - Live Stats ⚽🏆

A dynamic and modern web page displaying the current standings and detailed player statistics of the Turkish Super League.

[🚀 Click Here for Live Demo](https://rcerdihan.github.io/tsl/)

## 🌟 Features
- **Live Standings:** Team rankings, matches played, wins/draws/losses, goals for/against, goal difference, and recent form (last 5 matches).
- **Player Statistics:** The league's top goalscorers and top assist providers (Top 5 format).
- **Team List:** An interactive grid layout featuring all competing teams in the Super League along with their official logos.
- **Fully Automated Data ⚡:** **Data is NEVER entered manually.** All stats are scraped live directly from the official TFF (Turkish Football Federation) website and fetched instantly via Google Sheets in CSV format.
- **Responsive Design:** Fully compatible and optimized for mobile, tablet, and desktop devices.

## 🛠️ Technologies Used
- **HTML5**
- **CSS3** (Flexbox & Grid architecture)
- **JavaScript** (Vanilla JS, Fetch API, Asynchronous Programming)
- **Data Source:** Live scraping from TFF & Google Sheets CSV Export

## ⚙️ How Does the System Work?
The project is built on a static architecture (frontend only). Instead of a traditional database, match data and statistics are automatically and continuously pulled live from the TFF website to a Google Spreadsheet. 
Using the JavaScript `fetch()` function, the CSV output of this spreadsheet is read, parsed using Regex and JS methods, and dynamically rendered into the HTML tables. **Zero manual data entry is required.**

## 👨‍💻 Developer
- [Regaip Cuma Erdihan](https://github.com/rcerdihan)
