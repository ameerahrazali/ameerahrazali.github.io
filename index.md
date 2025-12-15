---
layout: default
title: Ameerah Razali · Portfolio
description: Data storyteller, statistics graduate, and lifelong learner exploring the intersection of people, data, and machine learning.
---

<div class="profile-pic-container">
  <img src="https://avatars.githubusercontent.com/u/92135269?s=400&u=31d020baab290a4bcf0196685a401b5dc33bf869&v=4"
       style="height: auto; border-radius: 8px;" 
       alt="Ameerah Razali profile photo" />
</div>

# 👋 Hi, I'm Ameerah 

**Always learning, always becoming.**

---

## <span id="about-me">About Me</span> ✨

Welcome to my data portfolio!

<div class="justify-text">
{% capture about_me_text %}
I'm a Statistics graduate with a specialization in Big Data Analytics, passionate about turning raw data into meaningful narratives. Whether it’s modeling inflation trends, exploring public sentiment, or visualizing patterns in music and crime, I enjoy solving real-world problems through data.

I’m especially drawn to:
- 📊 **Data storytelling** that brings insights to life
- 🧠 **Statistical modeling** for forecasts and decisions
- 💡 **Process improvement** powered by evidence
- 🔎 Exploring the human side of data through **sentiment & behavioral analysis**

I have a growing interest in **data science**, particularly in applying **machine learning** to understand complex systems and drive better decisions. I'm constantly exploring new tools and techniques to deepen my skillset.

My current toolkit includes **R**, **Python**, **SQL**, **Power BI**, and **Markdown/HTML**. I believe in clean visuals, reproducible work, and making data accessible to all.
{% endcapture %}

{{ about_me_text | markdownify }}

</div>

---

## <span id="projects">Featured Projects</span> 📈📊🤖

### 📺 YouTube Global Statistics Report  
> _What drives subscriber growth on the world’s biggest platform?_

{% include collapsible_project.html
  summary_text="Click to expand/collapse project details"
  content="
  An interactive R Markdown analysis exploring patterns in subscriber count, content category, and geography — powered by bootstrap regression and statistical testing.

  📌 **Featured Visual:**

  ![YouTube Report Cover](https://raw.githubusercontent.com/ameerahrazali/global-youtube-statistics/main/assets/top_channel.gif)

  **Highlights:**
  - 🎶 **Entertainment and Music** lead in both views and subscribers.
  - 📉 **More uploads ≠ more subscribers** — the relationship is weak and nonlinear.
  - 🌍 **U.S. and India dominate** the top channel landscape.

  [🔗 View GitHub Repo](https://github.com/ameerahrazali/global-youtube-statistics)
  [📄 Read the Report on RPubs](https://rpubs.com/ameerahrazali/youtube-stats-analysis)

  ![R Badge](https://img.shields.io/badge/Tool-R%20Markdown-blue?logo=r)
  ![Bootstrap Badge](https://img.shields.io/badge/Method-Bootstrap%20Regression-orange)
  ![YouTube Badge](https://img.shields.io/badge/Domain-YouTube%20Analytics-red)
  "
%}

---

### 🚨 Boston Public Safety Dashboard  
> _How can public crime data reveal safer paths forward?_

{% include collapsible_project.html
  summary_text="Click to expand/collapse project details"
  content="
  An interactive dashboard project analyzing **over 50,000 Boston crime records** using Power BI and Excel. Focused on uncovering crime hotspots, temporal patterns, and offense trends to support public safety decisions.
  
  📌 **Featured Visual:**
  
  ![Boston Dashboard Cover](https://raw.githubusercontent.com/ameerahrazali/boston-public-safety/main/assets/authority1_demo.gif)
  
  **Highlights:**
  - 🕓 Crimes are most frequent between **10 AM – 10 PM**, peaking around **4 PM**.
  - 🔍 Common offenses include **larceny**, **assault**, and **drug violations**.
  - 🗺️ Maps and filters help identify **high-risk neighborhoods** and time zones.

  [🔗 View GitHub Repo](https://github.com/ameerahrazali/boston-public-safety)
  
  ![Power BI Badge](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)  
  ![Excel Badge](https://img.shields.io/badge/Tool-Microsoft%20Excel-green?logo=microsoft-excel)  
  ![Crime Badge](https://img.shields.io/badge/Domain-Crime%20Analytics-red)
  "
%}


---

### 🎧 Spotify Streaming Analysis 2024  
> _Can streaming features help predict whether a song is explicit?_

{% include collapsible_project.html
  summary_text="Click to expand/collapse project details"
  content="
  This project analyzes Spotify’s 2024 streaming data to classify tracks as explicit or not. The analysis involved data cleaning, EDA, and applying supervised learning models — all performed in Python.

  📌 **Featured Visual:**
  
  ![Spotify Analysis Cover](https://raw.githubusercontent.com/ameerahrazali/spotify-streams/main/assets/spotify_analysis.png)
  
  **Highlights:**
  - ⚖️ Addressed **class imbalance** using **Balanced Random Forest** and baseline Logistic Regression.
  - 📊 Included **ROC curve evaluation** and comparison between models.
  - 🧹 Comprehensive preprocessing and EDA to understand feature distributions.
  
  [🔗 View GitHub Repo](https://github.com/ameerahrazali/spotify-streams)
  
  ![Python Badge](https://img.shields.io/badge/Tool-Python-blue?logo=python)  
  ![ML Badge](https://img.shields.io/badge/Model-Balanced%20Random%20Forest-green)  
  ![Spotify Badge](https://img.shields.io/badge/Domain-Spotify%20Analytics-black?logo=spotify)
  "
%}


---

### 📈 CPI Forecasting with ARIMA (Python)
> _How can past inflation data help us predict future trends?_

{% include collapsible_project.html
  summary_text="Click to expand/collapse project details"
  content="
  An end-to-end time series modeling project using **manual ARIMA tuning** and **backward stepwise regression** to forecast Malaysia’s Consumer Price Index (CPI). The final model was evaluated against actual CPI values from Sep 2023–Aug 2024.

  📌 **Featured Visual:**
  
  ![CPI ARIMA Forecast](https://raw.githubusercontent.com/ameerahrazali/malaysia-cpi-fnab-forecast/main/plots/cpi_forecast.png)
  
  **Highlights:**
  - 🔍 Built ARIMA(1,1,2) model manually with statistical testing (ADF, KPSS).
  - 📉 Included backward stepwise regression with lag features to optimize prediction.
  - 📊 Compared forecast results against actual CPI for accuracy assessment.
  
  [🔗 View GitHub Repo](https://github.com/ameerahrazali/malaysia-cpi-fnab-forecast)
  
  ![Python Badge](https://img.shields.io/badge/Tool-Python-blue?logo=python)  
  ![ARIMA Badge](https://img.shields.io/badge/Model-ARIMA(1,1,2)-purple)  
  ![Forecast Badge](https://img.shields.io/badge/Focus-Inflation%20Forecasting-lightgrey)
  "
%}


---

### 💬 Reddit Sentiment Analysis: Hump Day Yay or Nay?
> _Should Wednesdays be the new weekend?_

{% include collapsible_project.html
  summary_text="Click to expand/collapse project details"
  content="
  A lighthearted NLP project exploring Reddit sentiment toward a midweek break. Using over **1,100 comments** from a viral post on r/unpopularopinion, the analysis combines scraping, sentiment scoring, and quirky word clouds to uncover what the internet really thinks of **#MidweekReset**.

  📌 **Featured Visual:**
  
  ![Reddit Analysis Cover](https://raw.githubusercontent.com/ameerahrazali/wednesday-offs-sentiment/main/assets/wednesday_offs.png)
  
  **Highlights:**
  - 🧼 Full NLP pipeline: text cleaning, tokenizing, stopword removal.
  - 🧠 VADER sentiment scoring with **negation-aware processing**.
  - 📊 Violin plots and word clouds reveal emotional tones and common themes.
  - 🔍 Top-voted comments skewed **positive or neutral**, supporting midweek reset.
  
  [🔗 View GitHub Repo](https://github.com/ameerahrazali/wednesday-offs-sentiment)  
  
  ![Python Badge](https://img.shields.io/badge/Tool-Python-blue?logo=python)  
  ![VADER Badge](https://img.shields.io/badge/Sentiment-VADER-yellowgreen)  
  ![Reddit Badge](https://img.shields.io/badge/Data-Reddit%20API-orange)
  "
%}


---

### ⚾ MLB SQL Analysis
> _Exploring player performance with window functions and CTEs_

{% include collapsible_project.html
  summary_text="Click to expand/collapse project details"
  content="
  A structured SQL and Tableau project analyzing Major League Baseball (MLB) player data from Maven Analytics. The SQL portion focuses on player origins, salaries, and career spans using CTEs, window functions, and aggregation techniques. Tableau brings the findings to life through interactive visuals.
  
  📌 **Featured Visual:**
  
  ![MLB Dashboard Preview](https://raw.githubusercontent.com/ameerahrazali/mlb-analysis/main/assets/MLB_Salary.gif)

  **Highlights:**
  - 🧮 Applied `ROW_NUMBER`, `NTILE`, and `LAG` to analyze debut/final games and career lengths.
  - 🏫 Identified top schools producing high-earning, long-career MLB players.
  - 💸 Explored team salary distributions and milestone thresholds (**$1B+ in salary spend**).  
  - 📊 Built a Tableau dashboard featuring:
    - Treemap of **top 10 salary-producing schools**  
    - Funnel from **schools to $5M+ players**  
    - Scatter plot of **career span vs. school salary**  
    - Choropleth map of **player origins by state**  
    - Bar chart of **top schools by career longevity**
  
  [🔗 View Project](https://github.com/ameerahrazali/mlb-analysis)
  
  ![SQL](https://img.shields.io/badge/Language-SQL-blue?logo=mysql)  
  ![CTE](https://img.shields.io/badge/Concepts-CTE%2C%20Window%20Functions-orange)  
  ![MLB](https://img.shields.io/badge/Data-MLB-lightgrey)
  ![Tableau](https://img.shields.io/badge/Visualization-Tableau-blueviolet?logo=tableau)
  "
%}

---

## <span id="reach-me">Reach Me</span> 📧

<p align="left">
  <a href="https://github.com/ameerahrazali" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
  </a>
  <a href="https://www.linkedin.com/in/ameerahrazali" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</p>

---

### ☕ Thank You

Appreciate you stopping by!  
Whether it's building models or making sense of meme sentiment, I love bringing data to life — usually with a strong coffee in hand.  
Let’s chat if you're into dashboards, storytelling, or data that makes you go “huh, interesting.”

_Chasing patterns, questions, and great coffee,_  
**— Ameerah**
