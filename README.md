# Sleep Data Tracking Project

This project is based on a two-month period during the summer of 2023 when I began tracking my own sleep habits to improve my sleep health. I logged bedtime, wake time, screen time, and caffeine intake daily and rated how I felt each morning. 

My goal was to improve health.

---

## Dataset

The dataset includes 61 consecutive days (June 1 – July 31, 2023). For each day, I recorded:

**Columns:**
- `Date`: Calendar day of the entry  
- `Bedtime`: Time I went to bed (12-hour format)  
- `Wake Time`: Time I woke up  
- `Sleep Duration (hrs)`: Calculated total hours of sleep  
- `Screen Time Before Bed (hrs)`: Estimated time on phone/laptop before bed  
- `Caffeine After 3PM`: Whether I had caffeine after 2PM that day (`Yes`/`No`)  
- `Sleep Quality (1–5)`: Subjective rating (see scale below)

## Sleep Quality Scale (1–5)

Self-assigned score based on how rested I felt upon waking
| Rating | Description                          |
|--------|--------------------------------------|
| 5      | Extremely well rested, energetic     |
| 4      | Slept well, felt good                |
| 3      | Okay sleep, average rest             |
| 2      | Restless, not fully rested           |
| 1      | Poor sleep, exhausted                |

---

## Visualizations

All charts were created in Excel based on the dataset

Highlighted some key patterns:
- Correlation between Sleep Duration and Quality  
- Average Sleep Quality and Sleep Duration — Caffeine vs No Caffeine  
- Screen Time vs Sleep Quality  

---

## Key Insights

- Sleep quality was significatly lower on days with:
  - Caffeine after 2 PM  
  - Screen time over 2 hours before bed  
- The best sleep occurred when:
  - Bedtime was before midnight  
  - No caffeine was consumed  
  - Screen time was under 1 hour

---

## Reflection

Realizing that caffeine and screen time were directly affecting my sleep quality, and how I felt throughout the day, helped me make healthier changes.

This wasn’t originally intended to be a data science project. It started as a personal habit tracker. Analyzing patterns and building visualizations showed me how powerful data can be in understanding and improving everyday life.
