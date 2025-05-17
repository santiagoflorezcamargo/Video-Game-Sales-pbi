# Global Video Game Sales Analysis (1980–2020)

A full-stack exploration of global video game sales from 1980 to 2020 using MySQL for data preparation and Power BI for interactive reporting.

---

## 📑 Table of Contents

1. [Objective](#objective)  
2. [Executive Summary](#executive-summary)  
3. [Worldwide Insights](#worldwide-insights)  
4. [Regional Breakdown](#regional-breakdown)  
5. [Trends Over Time](#trends-over-time)  
6. [Variability & Outliers](#variability--outliers)  
7. [Conclusions & Recommendations](#conclusions--recommendations)  
8. [Additional Insights](#additional-insights)  
9. [Files & Structure](#files--structure)  
10. [Requirements & Usage](#requirements--usage)  
11. [License](#license)  
12. [Contact](#contact)  

---

## Objective

The primary objective of this project is to analyze and visualize global video game sales trends—by region, platform, genre, and title—from 1980 through 2020, extracting actionable insights to guide product strategy, marketing and market expansion.

---

## Executive Summary

- **Total units sold:** 8,820.36 M worldwide (1980–2020).  
- **Top region:** North America with 4,333.43 M units (49.15 % of global).  
- **Top platform:** PlayStation 2 at 1,233.46 M units.  
- **Top title:** Wii Sports at 82.74 M units.  
- **Peak year:** 2008 at 678.90 M units.  
- **Since 2017:** Sales have declined—mobile/free-to-play impact.  

_For full visuals and deep-dive, see the PDF and Power BI report._

---

## Worldwide Insights

- **Top 10 Platforms:** PS2, X360, PS3, Wii, DS…  
- **Top Titles:** Wii Sports, GTA V, Super Mario Bros…  
- **Top Publishers:** Nintendo (1,784.43 M), EA (1,093.39 M), Activision (721.41 M).  
- **Genre Breakdown:** Action leads (1,722.88 M; 19.53 %), followed by Sports and Shooter.  

---

## Regional Breakdown

- **Market share:** NA 49.15 %, EU 27.33 %, JP 14.57 %, Other 8.95 %.  
- **Publisher leaders by region:**  
  - NA/EU: Nintendo, EA, Activision…  
  - JP: Nintendo, Bandai Namco, Konami…  
  - Other: EA, Nintendo, Activision…  
- **Genre vs. region:**  
  - NA/EU/Other: Action top.  
  - JP: Role-Playing top.  

---

## Trends Over Time

- **Regional shifts:**  
  - 1980–1995: NA & JP neck-and-neck.  
  - 1996–2015: NA always #1.  
  - 2016: EU briefly overtakes.  
- **Platform lifecycles:** PS2 → Wii → X360/PS3 → DS/PS4…  
- **Genre golden era:** 2005–2011 peak for Action, Sports, Shooter, Role-Playing.  

---

## Variability & Outliers

- **NA vs. JP scatter:** Low correlation—cultural divergence.  
- **NA vs. EU scatter:** High correlation—similar markets.  
- **Boxplots:**  
  - Genres: high IQR (658.83); no extreme outliers.  
  - Platforms: right-skewed, 6 major outliers (PS2, X360…).  
  - Publishers: skewed distributions driven by mega-hits.  

---

## Conclusions & Recommendations

### Key Conclusions

1. North America dominates with ~49 % of all sales.  
2. PS2 is the historic best-seller at ~14 % of total console revenue.  
3. Action titles represent nearly 20 % of all game sales.  
4. Sales peaked in 2008; a downward trend emerges post-2016.  
5. High dispersion (>300 % CV) signals a mix of mega-hits vs. niche titles.

### Recommendations

- **Market expansion:** Accelerate campaigns in Europe & Japan for strong NA titles.  
- **Product focus:** Invest in growing genres (Racing, RPG).  
- **Portfolio optimization:** Replicate low-variance, steady-performers.  
- **Predictive analytics:** Build ML models to forecast regional sales.

---

## Additional Insights

- **Platform share by genre** chart: % breakdown of each platform within genres.  
- **Top 3 games by year** small-multiples: annual champions 1980–2020.  
- **Mario’s impact in Platform genre**: 36.44 % of all Platform sales.

---

## Files & Structure

