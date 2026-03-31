# ⚽ Sports Performance Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Sport-Football%20%2F%20Soccer-1DB954?style=for-the-badge&logo=fifa&logoColor=white" alt="Football"/>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License"/>
</p>

<p align="center">
  <b>An interactive Power BI dashboard for in-depth Football / Soccer performance analytics — covering player stats, team comparisons, live match data, and dynamic visualizations.</b>
</p>

---

## 📸 Dashboard Preview

> *Below are representative previews of the type of analytics and visuals this dashboard delivers.*

### 🏟️ Overview — Match & League Analytics
![Dashboard Overview](https://community.fabric.microsoft.com/t5/image/serverpage/image-id/250001iF79DC3BED7E58BD3/image-size/large?v=v2&px=999)

---

### 📊 Player Performance Stats
![Player Stats](https://radacad.com/wp-content/uploads/2014/07/report2.png)

---

### ⚔️ Team Comparison View
![Team Comparison](https://community.fabric.microsoft.com/t5/image/serverpage/image-id/321764i9E3CA2ABA3C94A03/image-size/large?v=v2&px=999)

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Dashboard Pages](#-dashboard-pages)
- [Data Sources](#-data-sources)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 📌 About the Project

The **Sports Performance Dashboard** is a comprehensive Power BI solution designed to give football analysts, coaches, and fans a 360° view of the beautiful game. From individual player metrics to full team head-to-head comparisons and match-day data, this dashboard turns raw football statistics into actionable visual insights.

Whether you're scouting a player, comparing two rival clubs, or tracking a team's form over a season — this dashboard has you covered.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🧍 **Player Performance Stats** | Goals, assists, pass accuracy, dribbles, tackles, and more — per player |
| ⚔️ **Team Comparison** | Side-by-side metrics for any two teams across key performance indicators |
| 📡 **Live / Match Data** | Real-time or recent match scores, results, and fixture data |
| 📈 **Charts & Visualizations** | Bar charts, radar charts, heatmaps, trend lines, and KPI cards |
| 🔍 **Interactive Filters** | Slice data by season, league, team, position, and date range |
| 🏆 **League Standings** | Dynamic table with points, wins, losses, goal difference |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Microsoft Power BI Desktop** | Dashboard design, DAX measures, data modelling |
| **Power Query (M Language)** | Data transformation and cleaning |
| **DAX (Data Analysis Expressions)** | Custom KPIs and calculated columns |
| **Excel / CSV** | Underlying data sources |

---

## 🚀 Getting Started

### Prerequisites

- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/en-us/downloads/) (free) — latest version recommended
- Git (to clone the repository)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/SatyendraPrajapati456/Sports_Performance_DashBoard.git

# 2. Navigate into the project folder
cd Sports_Performance_DashBoard
```

### Opening the Dashboard

1. Launch **Power BI Desktop**.
2. Go to **File → Open Report** and select the `.pbix` file from the cloned folder.
3. If prompted, refresh the data source connections.
4. Explore the dashboard pages using the navigation tabs at the bottom.

---

## 📂 Dashboard Pages

```
Sports Performance Dashboard
│
├── 🏠  Home / Overview          → Key metrics at a glance
├── 🧍  Player Stats             → Individual player performance breakdown
├── ⚔️  Team Comparison          → Head-to-head team analytics
├── 📡  Match Data               → Live scores & recent fixtures
└── 📈  Trends & Visualizations  → Season trends, form charts, heatmaps
```

---

## 📊 Data Sources

The dashboard is powered by football statistics data which may include:

- **Match results** — Scores, venues, dates, referees
- **Player data** — Goals, assists, minutes played, cards, shots on target
- **Team data** — Possession, passes, xG (expected goals), defensive stats
- **League tables** — Standings, points, goal difference

> 📝 *Data files are included in the `/data` directory of this repository (CSV / Excel format).*

---

## 🗂️ Project Structure

```
Sports_Performance_DashBoard/
│
├── 📁 data/                    # Raw and cleaned data files (.csv / .xlsx)
├── 📁 assets/                  # Images, icons, and background assets
├── 📄 Sports_Dashboard.pbix    # Main Power BI report file
└── 📄 README.md                # Project documentation
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the dashboard or add new features:

1. **Fork** the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m "Add: your feature description"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a **Pull Request**

---

## 📃 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Satyendra Prajapati**

<p>
  <a href="https://github.com/SatyendraPrajapati456">
    <img src="https://img.shields.io/badge/GitHub-SatyendraPrajapati456-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
</p>

---

<p align="center">⭐ If you found this project useful, please consider giving it a star!</p>
<p align="center">Made with ❤️ and ⚽ by Satyendra Prajapati</p>
