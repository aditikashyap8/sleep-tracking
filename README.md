# Sleep Data Tracking Project

This project is based on a two-month period during the summer of 2023 when I began tracking my own sleep habits to improve my sleep health. I logged bedtime, wake time, screen time, and caffeine intake daily and rated how I felt each morning.

What began as a self care experiment turned into my first data project and the experience that sparked my interest in data science.

---

## Dataset

**Dates Tracked:** June 1 – July 31, 2023  
**File:** [`sleep_data_2months_basic.xlsx`](./sleep_data_2months_basic.xlsx)

**Columns:**

- `Date`: Calendar day of the entry  
- `Bedtime`: Time I went to bed (12-hour format)  
- `Wake Time`: Time I woke up  
- `Sleep Duration (hrs)`: Calculated total hours of sleep  
- `Screen Time Before Bed (hrs)`: Estimated time on phone before bed  
- `Caffeine After 3PM`: Whether I had caffeine after 2PM (`Yes`/`No`)  
- `Sleep Quality (1–5)`: How rested I felt in the morning (see scale below)

---

## Sleep Quality Scale (1–5)

| Rating | Description                          |
|--------|--------------------------------------|
| 5      | Extremely well rested, energetic     |
| 4      | Slept well, felt good                |
| 3      | Okay sleep, average rest             |
| 2      | Restless, groggy, not fully rested   |
| 1      | Poor sleep, exhausted                |

---

## Visualizations

All charts were created in Excel based on the dataset:

- **Line Chart:** Sleep Duration over time  
- **Bar Chart:** Average Sleep Quality — Caffeine vs No Caffeine  
- **Scatter Plot:** Screen Time vs Sleep Quality  
- **Pie Chart:** % of Days with Late Caffeine  

---

## Key Insights

- Sleep quality was lower on days with:
  - Caffeine after 2 PM  
  - Screen time over 2 hours before bed  
- The best sleep occurred when:
  - Bedtime was before midnight  
  - No caffeine was consumed  
  - Screen time was under 1 hour

---

## Reflection

This wasn’t meant to be a data science project — it was just a personal tracker. But once I started seeing patterns and making charts, I realized how data could help me improve my life.

This spreadsheet — made before I ever studied analytics — sparked my passion for data and led me to major in **Data Science & Economics**.

---

## Files

- [`sleep_data_2months_basic.xlsx`](./sleep_data_2months_basic.xlsx) — Full dataset + charts
