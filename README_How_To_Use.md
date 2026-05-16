# National Club Management Dashboard — How to Use

A professional one-screen analytics dashboard for club/player data.  
The dashboard works with sample data, Google Sheets CSV links, or pasted raw CSV data.

---

## 1. Open the Dashboard

### Option A: Open Locally

1. Download the project files.
2. Make sure the main dashboard file is named:

```text
index.html
```

3. Double-click `index.html`.
4. The dashboard will open in your browser.
5. If you do not connect your own data, the dashboard will automatically load sample data.

### Option B: Open the Live Demo

If the project is published with GitHub Pages, open the live demo link:

```text
https://your-username.github.io/national-club-dashboard/
```

---

## 2. Use Sample Data

When the dashboard opens for the first time, it automatically generates sample club/player data.

You can use the sample data to test:

- KPI cards
- Charts
- Filters
- Top players table
- Auto insights
- Data quality section
- Export buttons
- Dark and light mode

---

## 3. Connect Google Sheets Data

The dashboard can connect to a published Google Sheet CSV link.

### Step 1: Prepare your Google Sheet

Your sheet should include columns such as:

```text
Player_ID
Name
Age
Gender
Club
Game
Level
Experience
Score
Membership_Status
City
Country
Join_Date
```

The dashboard can still work if some columns are missing, but using these columns gives the best results.

### Step 2: Publish the Google Sheet as CSV

In Google Sheets:

```text
File → Share → Publish to web
```

Then:

1. Choose the sheet/tab you want to publish.
2. Choose CSV format.
3. Click Publish.
4. Copy the published CSV link.

### Step 3: Load the Google Sheet in the Dashboard

1. Open the dashboard.
2. Click **Connect Sheet**.
3. Paste your published Google Sheet CSV link.
4. Click **Load Club Data**.
5. The dashboard will update automatically.

---

## 4. Paste Raw CSV Data

You can also paste CSV data manually.

1. Open the dashboard.
2. Click **Connect Sheet**.
3. Paste your raw CSV data into the CSV text area.
4. Click **Load Club Data**.

Example CSV format:

```csv
Player_ID,Name,Age,Gender,Club,Game,Level,Experience,Score,Membership_Status,City,Country,Join_Date
NC0001,Ahmed Hassan,24,Male,National Club,Football,Advanced,6,88,Active,Cairo,Egypt,2021-03-15
NC0002,Sara Ali,21,Female,Al Ahly,Tennis,Professional,8,94,Premium,Giza,Egypt,2020-06-10
```

---

## 5. Use the Filters

The sidebar filters allow you to analyze specific groups of players.

You can filter by:

- Player level
- Game type
- Club
- Gender
- Membership status
- Age range
- Experience
- Minimum score
- Player name or ID

After changing any filter, the dashboard updates automatically.

To clear all filters, click:

```text
Reset All Filters
```

---

## 6. Read the KPI Cards

The KPI cards at the top show a quick summary of the current filtered data.

They include:

- Total Players
- Active Members
- Average Score
- Highest Score
- Average Age
- Top Club
- Top Game
- Premium Members
- Male/Female Ratio
- Best Level

When you apply filters, the KPI cards update instantly.

---

## 7. Read the Charts

The charts help you understand performance and distribution.

The dashboard includes:

- Average Score by Game
- Player Level Distribution
- Gender Split
- Club Performance
- Age Groups
- Membership Status
- Score by Experience
- Radar Chart
- Club × Game Heatmap

Use these charts to compare clubs, games, levels, and player performance.

---

## 8. Use the Top Players Table

The Top Players table shows the highest-performing players based on score.

The table includes:

- Rank
- Player ID
- Name
- Club
- Game
- Level
- Age
- Experience
- Score
- Status

You can use this section to quickly identify the best-performing players.

---

## 9. Use Auto Insights

The Auto Insights section gives quick recommendations and highlights.

It may show:

- Best performing club
- Weakest performing club
- Best performing game
- Lowest performing game
- Highest scoring player
- Player group needing attention
- Recommended focus area

These insights update when the filters change.

---

## 10. Check Data Quality

The Data Quality section helps you check the uploaded data.

It shows:

- Total loaded rows
- Filtered rows
- Missing values
- Duplicate Player_ID values
- Invalid score values
- Current data source
- Last loaded time

This helps confirm whether the data is clean and ready for analysis.

---

## 11. Export Data

The dashboard includes export options.

You can export:

- Filtered data as CSV
- Top players as CSV
- Dashboard as a printed page or PDF

Use these buttons when you want to share or save the results.

---

## 12. Switch Dark and Light Mode

Click the theme button in the top-right area to switch between:

- Dark mode
- Light mode

The charts and dashboard colors update automatically.

---

## 13. Recommended File Structure

For GitHub, use this structure:

```text
national-club-dashboard/
│
├── index.html
├── README.md
├── screenshot.png
└── sample-data.csv
```

---

## 14. Publish with GitHub Pages

To create a live demo:

1. Upload the project to GitHub.
2. Make sure the main file is named `index.html`.
3. Go to:

```text
Settings → Pages
```

4. Choose:

```text
Source: Deploy from a branch
Branch: main
Folder: / root
```

5. Save.
6. GitHub will generate a live demo link.

The live demo link will look like:

```text
https://your-username.github.io/national-club-dashboard/
```

---

## 15. Important Privacy Note

Do not upload private or real player/member data to a public GitHub repository.

Use:

- Sample data
- Fake data
- Anonymized data

GitHub Pages websites are public unless the repository and deployment settings are private.

---

## Author

Created by **Madonna Donna**.
