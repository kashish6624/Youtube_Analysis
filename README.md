# YouTube Tech Education Dashboard

This Power BI dashboard provides a **comprehensive visual analysis of educational tech content on YouTube**, focusing on programming skills, video performance, teaching quality, viewer behavior, and engagement trends over time.  
<img width="1299" height="731" alt="Screenshot 2025-07-13 233152" src="https://github.com/user-attachments/assets/6f2c2152-5f0e-4b68-b9ea-6011a6df386b" />

---

## What This Dashboard Does

This dashboard enables users to:

- Identify **top-performing YouTube channels** by total views and content volume.
- Analyze **teaching focus areas** across programming and AI topics.
- Understand **viewer engagement patterns** (time of day, video type, topic popularity).
- Compare **channel teaching effectiveness** using a combination of skill count and total views.
- Differentiate between **short-form and long-form content** and how they contribute to reach.
- Filter by **topic, channel, year, and video type** to explore performance metrics over time.

---

## Filters Available

- `Topic`: Select a programming language, technology, or skill (e.g., Python, SQL, AI).
- `Channel Name`: Focus on a specific YouTube channel.
- `Year`: Filter by year (shown: 2010–2013).
- `Video Type`: View statistics for Shorts vs Full-length videos.

---

## Dashboard Visuals

### Which Channel Has the Most Views?
- **Treemap** showing total views per channel.
- Top performers include:
  - Simplilearn
  - Coding Ninjas
  - Net Ninja
  - Neso Academy
  - CodeWithHarry

---

### Average Views of Topics Taught
- **Bar chart** showing average views per skill/topic.
- Popular topics:
  - C / C++
  - Python
  - SQL
  - Java
  - AI News

---

### Video Type Breakdown
- **Donut chart** comparing:
  - **Shorts**: 4.48K videos
  - **Full-length Videos**: 40.51K videos

---

### Which Skill Is Taught in How Many Videos?
- Bar chart displaying total video count per skill.
- Most taught:
  - `C`, `R`, `Python`, `Java`, `Go`, `PHP`, `AI`

---

### Channel Teaching Quality
- Combined **bar + line chart**:
  - **Bars**: Number of topics taught
  - **Line**: Total views per channel
  - Example channels: Simplilearn, Neso Academy, CodeWithHarry

---

### When Is Which Skill Studied the Most?
- **Heatmap** showing study patterns by hour of day:
  - Morning, Afternoon, Evening, Late Night
  - Example: C++ and Python are studied most during late-night hours.

---

## Insights

- **Simplilearn** dominates total viewership.
- **C, R, Python, and Java** are the most taught skills.
- **Shorts** comprise a small portion of the overall educational content.
- Late night is a **peak time** for self-learning among viewers.
- Several channels show both **high teaching output** and **strong viewer retention**.

---

## Tools & Technologies Used

- **Power BI**: Data modeling and dashboard visualization
- **Power Query** 
- **Data Sources**:
  - YouTube API
  - Web scraping tools (e.g., Selenium, BeautifulSoup)

