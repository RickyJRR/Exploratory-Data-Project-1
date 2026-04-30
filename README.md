# Exploratory-Data-Project-1
This project explores global tech layoff data using SQL, uncovering trends across companies, industries, countries, and time periods. The goal was to surface meaningful patterns from raw data — identifying who was hit hardest, when, and by how much.

What I Analyzed

Scale of layoffs — Identified the maximum total and percentage of workforce laid off across all companies
100% layoff events — Filtered companies that laid off their entire workforce, ranked by size and funds raised
Company-level totals — Ranked companies by total employees laid off
Industry impact — Aggregated layoffs by sector to identify the hardest-hit industries
Country breakdown — Compared layoff volumes across countries globally
Year-over-year trends — Grouped layoffs by year to track how the wave evolved over time
Monthly trends & rolling totals — Used a rolling SUM window function to visualize cumulative layoffs month by month
Top 5 companies per year — Used DENSE_RANK() with PARTITION BY to rank companies by layoffs within each year
