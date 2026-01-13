# OpenAI-Assisted Social Media Page Analysis Using Python

## Overview
This project performs an in-depth analysis of social media page data using
**Python**, with **OpenAI-assisted interpretation** for understanding patterns
in engagement, page categories, and content descriptions.

The focus of the project is **analysis and insight extraction**, not building
a recommendation or machine learning system.

---

## Project Objectives
- Load and structure raw social media page data
- Analyze engagement metrics such as followers, posts, and following
- Understand different types of social media pages (tech, media, lifestyle, community, etc.)
- Extract meaningful insights from page bios and metadata
- Demonstrate practical data analysis using Python fundamentals

---

## Dataset Description
Each record in the dataset represents a social media page and includes:
- `username`
- `name`
- `no_of_post`
- `no_of_followers`
- `no_of_following`
- `type_of_page`
- `bio`

The data reflects realistic social media profiles across multiple domains,
primarily focused on technology, startups, media, and lifestyle pages.

---

## Analysis Performed
- Identification of high-engagement pages based on follower count
- Comparison of posting activity across different page categories
- Grouping pages by type (Engineer, Media, Community, Creator, etc.)
- Exploration of bio text to understand content focus and themes
- Filtering and sorting pages based on engagement thresholds

---

## Role of OpenAI
OpenAI was used as an **assistance tool** to:
- Help interpret patterns observed in the data
- Improve structuring and explanation of analysis
- Enhance documentation clarity

All data processing and analysis logic is implemented manually using Python.

---

## Project Structure
```yaml
OpenAI_Assisted_Social_Media_Page_Analysis/
│
├── data/
│   ├── data.json          # Raw social media page data
│   └── finaldata.txt      # Cleaned / structured dataset
│
├── OpenAI_Social_Media_Page_Analysis.ipynb
│                          # Main notebook for data analysis
│
├── PROJECT_REPORT.md      # Detailed project report
└── README.md              # Project overview and documentation
```
---
## Technologies Used
- Python 3
- JSON
- Jupyter Notebook
- OpenAI (for analysis assistance, not automation)

---

## Why This Project
This project emphasizes:
- Working with real-world style social media data
- Strong Python fundamentals
- Analytical thinking over model hype
- Clear and explainable insights

It is designed as a **personal exploratory data analysis project**.

---

## Author
Yash Kanade