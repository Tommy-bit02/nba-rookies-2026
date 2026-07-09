# 🏀 2026 NBA Draft Class Analytics
### Rookie Ceilings · Summer League Predictions · Team Chemistry · First NBA Game Projections

> ⚠️ Portfolio & educational use only. Data sourced from NBA.com, ESPN, CBS Sports, and Basketball Reference. Projections are analytical estimates, not guarantees. Not affiliated with the NBA.

---

## 📌 Project Overview

The 2026 NBA Draft class was one of the most anticipated in recent memory — headlined by a Big 3 of AJ Dybantsa, Darryn Peterson, and Cameron Boozer whose superstar potential has been tracked since high school. This project analyzes the **real 2026 draft results**, projects Summer League and NBA Game 1 performance, models ceiling vs floor for each top pick, and evaluates how well each rookie's team situation sets them up to succeed.

**Key finding:** AJ Dybantsa leads all rookies with a 65% All-Star probability and a projected 18.2 PPG in Summer League — the highest ceiling in a historically deep class.

---

## 📊 Key Visualizations

### Chart 1 — Draft Overview: Ceilings, Summer League & Team Chemistry

![Draft Overview](chart1_draft_overview.png)

**Reading this chart:**
- **Top:** NBA ceiling score vs floor for all 10 picks — colored by team
- **Middle-left:** Summer League → Game 1 → Year 1 scoring projections side by side
- **Middle-right:** All-Star odds pie for top 5 picks — Dybantsa leads at 65%
- **Bottom:** Team chemistry and roster fit scores with mentor star for each rookie

---

### Chart 2 — Development Arcs, Scoring Reduction & Game 1 Predictions

![Development Arcs](chart2_development_arcs.png)

**Reading this chart:**
- **Top-left:** College PPG vs Year 1 NBA projection — the ~35% scoring reduction rookies typically face
- **Top-right:** Position breakdown of the top 10 picks
- **Bottom:** NBA Game 1 point predictions ranked — Dybantsa projected 14.5 pts in his debut

---

## 📈 2026 Draft Results & Projections

| Pick | Player | Team | Ceiling | Summer Proj | Game 1 Proj | Comp |
|------|--------|------|---------|------------|------------|------|
| #1 | AJ Dybantsa | Washington Wizards | **9/10** | 18.2 PPG | 14.5 pts | Tracy McGrady |
| #2 | Darryn Peterson | Utah Jazz | 8/10 | 16.8 PPG | 13.2 pts | Devin Booker |
| #3 | Cameron Boozer | Memphis Grizzlies | 8/10 | 15.4 PPG | 12.8 pts | Draymond Green |
| #4 | Caleb Wilson | Chicago Bulls | 8/10 | 14.2 PPG | 11.4 pts | Scottie Barnes |
| #5 | Keaton Wagler | LA Clippers | 7/10 | 12.8 PPG | 10.2 pts | Austin Reaves |
| #6 | Mikel Brown Jr. | Brooklyn Nets | 7/10 | 11.4 PPG | 9.8 pts | Jalen Brunson |
| #7 | Darius Acuff Jr. | Sacramento Kings | 7/10 | 13.2 PPG | 11.2 pts | Jordan Poole |
| #8 | Kingston Flemings | Atlanta Hawks | 7/10 | 12.1 PPG | 10.4 pts | Josh Hart |
| #9 | Morez Johnson Jr. | Dallas Mavericks | 8/10 | 10.8 PPG | 8.8 pts | Walker Kessler |
| #10 | Nate Ament | Milwaukee Bucks | 7/10 | 11.6 PPG | 9.6 pts | Jaren Jackson Jr. |

---

## 🏀 Summer League — Las Vegas Jul 9–19, 2026

> Dybantsa's first real test of NBA action begins at Summer League in Las Vegas, where he faces Peterson, Boozer, Wilson, and Acuff Jr. — the most hyped Summer League field in years.

### Best Team Situations (Chemistry Score)
- 🥇 **Cameron Boozer / Memphis** (9/10) — Clean role, Zach Edey mentor, clear path to starter
- 🥈 **Morez Johnson / Dallas** (9/10) — Reunited with coach Dusty May, Cooper Flagg as mentor
- 🥉 **Nate Ament / Milwaukee** (9/10) — Giannis as mentor, championship culture

---

## 🔬 Methodology

**Ceiling Score** = Composite of athleticism, skill, age, position value, and NBA fit based on scout consensus

**Summer League Projection** = College efficiency × position adjustment × team context factor

**NBA Game 1 Projection** = Summer League performance × rookie debut regression (historical avg: 78% of SL output)

**Year 1 Average** = College PPG × 0.65 typical NBA translation rate ± situation adjustment

**All-Star Odds** = Ceiling score × team development rating × historical position comp outcomes

**Citations:**
> [1] NBA.com 2026 Draft Results — nba.com/news/2026-nba-draft-order
> [2] ESPN Draft Grades — Jeremy Woo Big Board 2026
> [3] CBS Sports — 2026 pick-by-pick draft grades
> [4] Basketball Reference — College stats 2025-26

---

## 🚀 Setup

```bash
git clone https://github.com/Tommy-bit02/nba-rookies-2026.git
cd nba-rookies-2026
pip install -r requirements.txt
python src/01_pipeline.py
```

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)

---

*Part of a multi-domain data science portfolio. Companion projects: [Timberwolves Analytics](https://github.com/Tommy-bit02/timberwolves-analytics) · [Kawhi Injury Analytics](https://github.com/Tommy-bit02/kawhi-injury-analytics) · [Sports Sentiment & Revenue](https://github.com/Tommy-bit02/sports-sentiment-revenue)*
