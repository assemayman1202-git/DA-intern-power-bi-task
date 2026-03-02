# 📊 Social Media Sentiment Dashboard — Power BI
> **Codveda Internship — Final Task** | Interactive dashboard analyzing social media sentiment across 33 countries (2010–2023)

---

## 📋 Project Overview

This project analyzes how people **feel and interact** on social media platforms over 13 years.
The dashboard measures sentiments (Positive / Negative / Neutral) and reactions (Likes & Retweets) across Facebook, Instagram, and Twitter.





---

## 🗂️ Dashboard Pages

The dashboard consists of **2 pages:**

| Page | Focus |
|------|-------|
| **Sentiments** | Sentiment analysis by platform, country, and time |
| **Reactions** | Likes, Retweets, and engagement patterns |

---

## 📈 Key KPIs

| Metric | Value |
|--------|-------|
| 🌍 Countries | 33 |
| 💬 Total Sentiments | 732 |
| ❤️ Total Likes | 31K |
| 🔁 Total Retweets | 16K |

---

## 🧠 Page 1 — Sentiments



![Sentiment Page](https://raw.githubusercontent.com/assemayman1202-git/DA-intern-power-bi-task/main/Sentiment%20Page.png)



### Sentiment Distribution
| Sentiment | Count | % |
|-----------|-------|---|
| ❌ Negative | 425 | 58.06% |
| ➖ Neutral | 179 | 24.45% |
| ✅ Positive | 128 | 17.49% |

> ⚠️ **Key Insight:** Over 58% of content was Negative — a significant finding that raises questions about user behavior and platform dynamics.

---

### Sentiment by Date (2010–2023)
- Activity was **very low** from 2010–2020
- **Massive spike in 2022** — likely driven by major global events and the rapid growth of mobile usage
- Reflects how social media penetration was limited in the early 2010s

---

### Top Countries by Sentiment
1. 🇺🇸 USA — by far the highest
2. 🇬🇧 UK
3. 🇨🇦 Canada
4. 🇦🇺 Australia
5. 🇮🇳 India

> English-speaking countries dominate social media activity.

---

### Sentiment by Platform
| Platform | Activity |
|----------|---------|
| Instagram | Highest (~270) |
| Twitter | Second (~250) |
| Facebook | Third (~230) |

> Platforms are fairly balanced, with Instagram slightly ahead following its major growth surge post-2016.

---

## 💥 Page 2 — Reactions



![Reactions Page](https://raw.githubusercontent.com/assemayman1202-git/DA-intern-power-bi-task/main/Reactions%20page.png)




### Likes by Platform
| Platform | Likes | % |
|----------|-------|---|
| 📸 Instagram | 12K | 37.04% |
| 🐦 Twitter | 10K | 32.16% |
| 👥 Facebook | 10K | 30.80% |

> Instagram leads in Likes, confirming its dominance in engagement.

---

### Engagement Patterns

**By Hour:**
- Peak activity: **midday (10:00–15:00)**
- Secondary peak: **evening (~19:00)**
- People engage most during lunch breaks and early evening rest time

**By Day:**
- Activity is relatively consistent across all days
- Slight peaks on **Saturday and Sunday** (weekend effect)

---

### Likes & Retweets Relationship
- Strong **positive correlation** between Likes and Retweets
- Content that resonates emotionally gets both liked AND shared
- Users retweet posts that reflect their own mood or situation

---

## 🔑 Key Insights

| # | Insight |
|---|---------|
| 1 | **58% Negative content** — majority of social media expression is negative, worth deeper investigation |
| 2 | **2022 saw a massive spike** — what happened? Major events drove unprecedented engagement |
| 3 | **USA dominates** by a large margin — English-speaking countries lead activity |
| 4 | **Instagram is #1** in both activity and likes |
| 5 | **Midday is peak time** — best window for content publishing |
| 6 | **Likes drive Retweets** — emotional content gets amplified |

---

## 🛠️ Tools Used

```
Power BI Desktop   → Dashboard creation & visualization
Power BI Service   → Publishing & sharing
DAX                → Calculated measures
```

---

## 📁 Project Structure

```
social-media-sentiment-dashboard/
│
├── 2nd_task_intern.pbix     # Power BI Dashboard file
└── README.md                # This file
```

---

## 🚀 How to View

1. Download `2nd_task_intern.pbix`
2. Open with **Power BI Desktop** (free download from Microsoft)
3. Or view the published report via the shared link

---

*Codveda Data Science Internship — Task 2*
