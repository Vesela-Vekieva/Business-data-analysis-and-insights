# Business Data Analysis & Insights
### Event Performance Analysis: Player Behavior & Monetization

## Project Overview

This project analyzes player behavior and monetization performance during a special in-game event.

The objective was to identify:

- Player drop-off patterns
- High-friction missions
- Revenue generation drivers
- Monetization opportunities
- Event optimization recommendations

The analysis combines player progression data, mission skip behavior, and revenue metrics to uncover actionable business insights.

---

## Business Problem

Game events often generate large amounts of player interaction data, but identifying where players disengage and what drives monetization remains challenging.

This analysis answers key questions such as:

- Where do players drop off during the event?
- Which missions create the highest friction?
- Which player segments generate the most revenue?
- How does monetization evolve throughout progression?
- Which monetization strategy performs better in an A/B test?

---

## Dataset

The dataset contains:

- 2,040 mission-level records
- Player level information
- Mission names
- Number of players starting missions
- Mission skips
- Skip costs in premium currency

Premium Currency Conversion:

```
100 Currency = $4.99
```

---

## Tools Used

- Microsoft Excel
- Pivot Tables
- Calculated Metrics
- Data Visualization
- Exploratory Data Analysis (EDA)

Potential alternative tools:

- SQL
- Python (Pandas, Matplotlib)
- Power BI
- Tableau

---

## Methodology

### Data Preparation

Created additional business metrics:

- Completion Rate
- Revenue per Mission
- Revenue per Skip

Player levels were grouped into progression ranges to identify behavioral trends across different stages of the event.

---

## Key Analyses

### 1. Player Drop-off Analysis

Analyzed skipped missions by level group to identify progression bottlenecks.

**Finding:**
Player drop-off is heavily concentrated in early event stages (Levels 2–11).

---

### 2. Revenue Analysis

Measured revenue generated through mission skips.

**Finding:**
Early levels generate the highest total revenue because most players reach them.

---

### 3. Revenue per Skip Analysis

Compared monetization efficiency across progression levels.

**Finding:**
Revenue per skip increases significantly in later levels.

Players who progress further demonstrate stronger spending behavior.

---

### 4. Mission-Level Friction Analysis

Identified missions with the highest player drop-off.

Top friction points included:

- Chapter1_mission4
- Chapter2_mission5
- Chapter2_mission6

These missions may contain difficulty spikes or progression barriers.

---

### 5. High-Value Mission Analysis

Analyzed revenue generated per skipped mission.

**Key Finding:**

Chapter5_mission17 generated the highest revenue per skip due to its significantly higher skip cost.

This highlights the impact of pricing strategy on monetization outcomes.

---

### 6. A/B Test Evaluation

Compared two monetization variants:

| Metric | Group A | Group B |
|----------|----------|----------|
| ARPDAU | $0.15 | $0.16 |
| ARPPU | $30 | $16 |

**Winner: Group B**

Although Group A generated more revenue per paying user, Group B achieved higher overall revenue per active user, indicating stronger monetization at scale.

---

## Key Findings

- Early-stage missions create the highest player friction.
- Early levels generate the largest share of total revenue.
- Revenue per skip increases with player progression.
- Later-stage players demonstrate higher monetization potential.
- Mission pricing significantly impacts revenue outcomes.
- Total event revenue reached **$224,111**.

---

## Recommendations

### Improve Early Progression

Reduce friction in early missions to improve retention.

### Optimize Difficulty Curve

Create smoother progression between missions.

### Encourage Deep Progression

Design incentives that motivate players to reach later stages.

### Refine Skip Pricing

Balance monetization opportunities without creating frustration.

### Expand Monetization Testing

Continue experimenting with offers, bundles, and microtransactions through A/B testing.

---

## Business Impact

The analysis demonstrates how player behavior data can be transformed into actionable business decisions that improve:

- Player retention
- Event engagement
- Revenue generation
- Monetization strategy
- Product design decisions

---


