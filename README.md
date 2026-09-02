# Optimizing Global Content Strategy & Revenue Potential for Digital Media Creators

Exploratory data analysis of a global YouTube channel dataset, examining how content
category, upload frequency, channel age, geography, and national demographics relate
to subscriber growth, view velocity, and estimated earnings.

## Problem Statement

Emerging YouTube creators and media networks need to understand how content category,
upload frequency, channel age, and national demographics interact to drive subscriber
growth, view velocity, and estimated earnings. Answering these relationships helps
creators decide where to focus their content, how frequently to publish, and what
monetization potential to expect based on global benchmarks.

## Dataset

Global YouTube Statistics dataset. Key columns used across this analysis:

| Column | Description |
|---|---|
| `category` | Content category / niche |
| `channel_type` | Broad channel format |
| `country` | Channel's country of origin |
| `uploads` | Lifetime video upload count |
| `subscribers` | Total subscriber count |
| `video_views` | Total lifetime views |
| `subscribers_for_last_30_days` | Subscribers gained in the last 30 days |
| `video_views_for_the_last_30_days` | Views gained in the last 30 days |
| `created_year` | Year the channel was created |
| `lowest_monthly_earnings` / `highest_monthly_earnings` | Estimated monthly earnings range |
| `lowest_yearly_earnings` / `highest_yearly_earnings` | Estimated yearly earnings range |
| `video_views_rank`, `country_rank`, `channel_type_rank` | Platform ranking fields |
| `tertiary_edu_enrollment_pct` | National tertiary education enrollment rate |
| `unemployment_rate` | National unemployment rate |
| `urban_population` | National urban population figure |

## Analytical Questions

1. **Category Monetization Efficiency** — Which categories generate the highest revenue relative to audience size, and which underperform despite high views?
2. **Upload Volume vs. Audience Growth** — Does upload volume correlate with 30-day subscriber/view growth, or does niche/quality matter more?
3. **Geographic Distribution & Revenue Benchmarking** — How do top channels differ by country, and how does region affect view-to-subscriber ratio and earnings?
4. **Channel Maturity vs. Growth Velocity** — Do older channels keep higher view momentum, or do newer channels grow faster short-term?
5. **Channel Type Performance Comparison** — How do ranking metrics vary by channel type, and which formats retain audiences best?
6. **Macroeconomic & Socioeconomic Drivers** — Do national indicators (education, unemployment, urbanization) correlate with channel density/earning power by country?

## Approach

- **Analysis**: Python (pandas, matplotlib, seaborn) — data cleaning, calculated fields (e.g., earnings-per-subscriber, view-to-subscriber ratio, channel age buckets), correlation analysis, grouped comparisons.
- **Dashboard**: Google Looker Studio — one page per question, with bar charts, scatter plots, a geo map, and cross-page filters (`category`, `country`, `channel_type`) for interactive exploration.
- **Reporting**: Word document (`Problem_Solution_Report.docx`) pairing each question with its approach and blank sections for findings/recommendations, filled in after analysis.

## Project Files

- `Problem_Report.docx` — Full narrative problem report (background, objectives, scope, methodology).
- `Problem_Solution_Report.docx` — Question-by-question template with analytical approach and fill-in-the-blank findings/recommendations.
- `analysis.py` / notebook — Python code for each of the six questions (correlation, grouping, visualization).
- Looker Studio dashboard — https://datastudio.google.com/reporting/33f0bb1b-5353-4a0a-9559-ef5d4ad0edae.

## Status

Analysis in progress. Findings and recommendations are being added to the report and
dashboard as each question is completed.

## Author

Ephraim — Software Engineering student, Admiralty University of Nigeria (ADUN)
