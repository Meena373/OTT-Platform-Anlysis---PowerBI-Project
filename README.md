# OTT-Platform-Anlysis---PowerBI Project
## Project objective:
The objective of this project is to design and develop a Power BI dashboard that:
•	Analyzes OTT content catalogs across multiple platforms such as Netflix, Amazon, Disnip+ Hotstar.
•	Identifies content distribution by genre, rating, country, and release year
•	Compares movies vs TV shows across platforms
•	Provides interactive filters for platform, genre, type, and title
•	Enables trend analysis for content growth over time
## Dataset:
1. <a href="https://www.kaggle.com/datasets/shivamb/netflix-shows">Netflix </a>
2. <a href="https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows">Amazon </a> 
3. <a href="https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows">Disnip+ Hotstar </a>
## Process:
1.	Load Data & Design Data Model – Imported the dataset into Power BI and structured an efficient data model.
2.	Data Cleaning with Power Query – Cleaned and transformed the data by analysis data types (dates, numbers, text), removing duplicates, renaming columns, and ensuring consistent formatting across all fields.
3.	DAX Measure Creation – Developed core measures using DAX functions such as CALCULATE, COUNT, and COUNTROWS to support KPI calculations and analytical insights.
4.	Interactive Dashboard Development – Built an interactive Power BI dashboard using KPIs, slicers, and different kind of visuals including bar charts, column charts, area charts, and donut charts for effective analysis.
## Dashboard:
Netflix
<img width="1328" height="751" alt="image" src="https://github.com/user-attachments/assets/fb757863-c6a6-4788-96f8-674b3414d424" />
Amazon
<img width="1332" height="747" alt="image" src="https://github.com/user-attachments/assets/514d74bc-4345-4450-bddf-cc2c5a453502" />
Hotstar
<img width="1330" height="747" alt="image" src="https://github.com/user-attachments/assets/ad04184d-7ce9-443b-978c-6a03c308bb31" />
## Project insight:
-	The dataset includes OTT content information such as, Platform (Disney+ Hotstar, Netflix, Amazon Prime), Content type (Movie / TV Show), Genre, Age rating, Country of production, Release year, Title information.
-	Key KPIs displayed include total number of titles, total movies and TV shows, total countries and total genres available across each OTT platform.
-	The dashboard provides:
- Platform-wise navigation using buttons for Home, Hotstar, Netflix, and Amazon
- Genre-wise content distribution to identify dominant genres such as Animation, Action, and Comedy **(Column Chart)**.
- Rating-wise content analysis highlighting different maturity ratings like TV-G, TV-PG, PG-13, and TV-14 **(Bar Chart)**.
- Movies vs TV Shows contribution to the overall content library **(Donut Chart)**.
- Country-wise content availability visualized using an **interactive map**.
- Release year trend analysis showing OTT content growth over time **(Area Chart).**
- Interactive slicers for content type, genre, title, and duration to enable detailed exploration.
- Year range slider to analyze content trends across different time periods.
## Conclusions:
The OTT Content Analytics Dashboard shows that movies make up the majority of OTT platform libraries. TV shows account for a smaller yet significant share. This indicates a strong focus on on-demand movie consumption. The rating-wise distribution indicates that most content is targeted toward general and teenage audiences. The sharp increase in titles released in recent years highlights rapid platform growth and rising competition. Geographical analysis shows that content is sourced from multiple countries. Overall, the dashboard clearly illustrates how Power BI can change OTT data into actionable insights for understanding content strategy, targeting audiences, and tracking platform growth trends.








