
# DailyDisplay

**Homepage:** [https://chevp.github.io/daily-display/index.html](https://chevp.github.io/daily-display/index.html)

## 1. Determine the Layout and Sequence

- **Screen Layout:** A simple full-screen layout that changes content every 2 minutes.
- **RSS News Feed:** Displayed for 2 minutes.
- **Daily Menu:** Displayed for 2 minutes.
- **Weather Forecast:** Displayed for 2 minutes.
- **Loop:** The content rotates in a continuous loop.

## 2. Components to Build the Feed

- **RSS News Feed:** Uses an RSS feed reader to fetch and format news articles for display.
- **Daily Menu:** A simple, updateable text file, spreadsheet, or Google Sheet that is read and displayed.
- **Weather Forecast:** Uses a weather API (like OpenWeatherMap) to fetch and display the current weather.

## 3. Backend Design

**Content Sources:**

- **RSS Feed:** Choose an RSS feed (e.g., from news websites) and use an RSS feed reader library to fetch articles.
- **Daily Menu:** Store the daily menu in a cloud-based file (Google Sheets, CSV, or a database) that is easy to edit. Google Sheets is recommended for easy, real-time updates.
- **Weather API:** Use a weather API to fetch the current forecast, updating in real-time or periodically.

## 4. Front-End Display

- Create a webpage or application that rotates between these content types every 2 minutes.
- Use JavaScript to manage transitions between screens with set intervals to change content.
- Apply CSS for styling to ensure readability and a clean layout on the screen.

## 5. Automatic Updates

- **RSS Feed:** Use JavaScript or a backend (Python or Node.js) to periodically fetch the latest articles.
- **Daily Menu:** Use Google Sheets API to pull the latest content and reflect changes in real-time without code updates.
- **Weather Forecast:** Call the weather API every 2-5 minutes to fetch the latest weather data.

## 6. Implementation Tools

- **RSS Feed:** JavaScript libraries like `rss-parser` or backend tools (like Python’s `feedparser`) can handle this.
- **Menu:** Use Google Sheets API or read from a CSV file using JavaScript or Python.
- **Weather API:** Use JavaScript (or Python) to call a weather API like OpenWeatherMap and display it.

## 7. UI Design

Each view should be tailored for readability and display:

- **RSS News Feed View:** A scrollable or static display of news headlines and summaries.
- **Daily Menu View:** A simple list showing breakfast, lunch, and dinner items.
- **Weather View:** Show current temperature, conditions (sunny, cloudy, etc.), and a daily forecast if desired.
- Aim for a clean, easy-to-read layout for visibility from a distance.

## 8. System Updates and Maintenance

- **Daily Menu Update:** Use Google Sheets or similar for daily updates, automatically fetching changes from the cloud.
- **RSS and Weather Updates:** Set these to automatically refresh at scheduled intervals (e.g., RSS feed every 15 minutes, weather every 2-5 minutes).

---

**Enjoy a streamlined, automated daily information display with DailyDisplay!**


