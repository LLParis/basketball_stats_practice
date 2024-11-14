<div align="center">

# 🏀 NBA Draft Data Scraper 

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Scrapy](https://img.shields.io/badge/Scrapy-2.5-brightgreen?style=for-the-badge&logo=scrapy)](https://scrapy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-purple?style=for-the-badge&logo=pandas)](https://pandas.pydata.org/)
[![Learning Project](https://img.shields.io/badge/Project%20Type-Learning-orange?style=for-the-badge)](https://github.com/yourusername)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://opensource.org/licenses/)

> A web scraping learning project to automate NBA draft data collection for my NBA Draft Success Model analysis

[Overview](#-overview) • [Features](#-features) • [Installation](#-installation) • [Learning Journey](#-learning-journey) • [Contributing](#-contributing)

<img src="https://user-images.githubusercontent.com/your-path/draft-banner.png" alt="NBA Draft Banner" width="800">

</div>

## 📝 Overview

This repository documents my journey learning web scraping through building an NBA draft data collector. Created as a solution to the time-consuming manual data collection process for my main [NBA Draft Success Model](your-link-here) project.

### 🎯 Project Goals
- Learn web scraping fundamentals with Python & Scrapy
- Automate collection of historical NBA draft data
- Create reliable data pipeline for draft analysis
- Practice modern data engineering techniques

## 🌟 Features

```mermaid
graph TD
    A[Basketball Reference] -->|Web Scraping| B[Data Collection]
    B -->|Learning Process| C[Data Processing]
    C -->|Scrapy| D[Player Stats]
    C -->|Python| E[Draft History]
    D --> F[Draft Success Model]
    E --> F
    style A fill:#f9f,stroke:#333
    style F fill:#bbf,stroke:#333
```

### Current Capabilities
- 📊 Extract draft pick details and statistics
- 🔄 Handle multi-team season data
- 📈 Process career trajectories
- 🧹 Basic data cleaning and formatting

### Learning Targets
- 🎯 Rate limiting and ethical scraping
- 🔍 Advanced CSS selectors
- 🕷️ Scrapy best practices
- 🗃️ Efficient data storage

## ⚙️ Technical Architecture

### Development Stack
```python
# Core Technologies
STACK = {
    'Language': 'Python 3.8+',
    'Scraping': 'Scrapy 2.5',
    'Data Processing': 'Pandas',
    'Learning Resources': [
        'Scrapy Documentation',
        'Web Scraping Tutorials',
        'NBA Stats API Guides'
    ]
}
```

### Project Structure
```bash
NBA_Draft_Scraper/
├── 🕷️ spiders/
│   └── nba_draft_spider.py     # Where I'm learning Scrapy
├── 📊 data/
│   └── draft_data.csv          # Collected data
├── 📝 README.md                # Project documentation
├── 🔧 requirements.txt         # Dependencies
└── ⚙️ settings.py              # Scrapy configurations
```

## 🚀 Installation

```bash
# Clone this learning project
git clone https://github.com/yourusername/NBA_Draft_Scraper.git

# Setup development environment
cd NBA_Draft_Scraper
pip install -r requirements.txt

# Run the scraper
scrapy crawl nba_draft_spider -o data/draft_data.csv
```

## 📊 Data Collection

### Sample Data Structure
### Sample Data Structure
| Column Name          | Description                            | Example     |
|----------------------|----------------------------------------|-------------|
| `player_id`          | Unique identifier for each player      | `1`         |
| `draft_year`         | Year the player was drafted            | `1995`      |
| `draft_round`        | Round in which the player was drafted  | `1`         |
| `draft_pick`         | Overall pick number in the draft       | `5`         |
| `team_drafted_by`    | Team that initially drafted the player | `GSW`       |
| `player_name`        | Name of the player                     | `Kevin Garnett` |
| `season_year`        | Season for the player’s stats          | `2004-05`   |
| `team`               | Team for the season                    | `MIN`       |
| `age`                | Player’s age during the season         | `28`        |
| `position`           | Position played during the season      | `PF`        |
| `games_played`       | Number of games played                 | `82`        |
| `games_started`      | Number of games started                | `82`        |
| `minutes_per_game`   | Average minutes per game               | `38.1`      |
| `points_per_game`    | Points scored per game                 | `22.2`      |
| `rebounds_per_game`  | Rebounds per game                      | `13.5`      |
| `assists_per_game`   | Assists per game                       | `5.7`       |
| `steals_per_game`    | Steals per game                        | `1.5`       |
| `blocks_per_game`    | Blocks per game                        | `1.4`       |
| `field_goal_percentage` | Field goal percentage             | `0.502`     |
| `three_point_percentage` | 3-point shooting percentage      | `0.240`     |
| `free_throw_percentage`  | Free throw percentage             | `0.811`     |
| `advanced_metrics`   | Advanced stats (e.g., PER, WS)         | `22.5 PER`  |
| `awards`             | Awards received during the season      | `MVP, All-NBA First Team` |

## 📚 Learning Journey

### Progress Tracker
- [x] **Week 1:** Basic HTML parsing & Scrapy setup
- [x] **Week 2:** Handling pagination & nested data
- [ ] **Week 3:** Rate limiting & data validation
- [ ] **Week 4:** Error handling & recovery
- [ ] **Week 5:** Performance optimization

### Key Learnings
```python
lessons_learned = {
    'Technical': [
        'Web scraping fundamentals',
        'Data pipeline design',
        'Error handling patterns'
    ],
    'Personal Growth': [
        'Project planning',
        'Documentation practices',
        'Community engagement'
    ]
}
```

## 🔮 Future Directions

### Learning Goals
- [ ] Advanced Scrapy techniques
- [ ] Automated testing
- [ ] CI/CD implementation
- [ ] Data validation frameworks

### Project Evolution
- [ ] Enhanced error recovery
- [ ] Parallel processing
- [ ] API development
- [ ] Real-time updates

## 🤝 Contributing

As a learning project, I welcome:
- Code reviews and feedback
- Optimization suggestions
- Documentation improvements
- Learning resources

## ⚖️ License

MIT License - See `LICENSE` for details

## ⚠️ Disclaimer

This educational project follows Basketball Reference's terms of service and implements appropriate request delays.

---

<div align="center">

### 📚 Learning Web Scraping Through NBA Analytics

[![GitHub followers](https://img.shields.io/github/followers/yourusername?style=social)](https://github.com/yourusername)
[![Project Stars](https://img.shields.io/github/stars/yourusername/NBA_Draft_Scraper?style=social)](https://github.com/yourusername/NBA_Draft_Scraper/stargazers)

</div>