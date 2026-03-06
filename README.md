# 🎬 Movies Dataset Exploration Dashboard

An interactive **Movie Dataset Exploration Dashboard built using Microsoft Excel** to explore movie industry trends, financial performance, and audience ratings through data-driven insights.

---

# 1. Project Title
**Movie Data Exploration and Visualization using MS Excel**

---

# 2. Project Description

This project analyzes a movie dataset to discover patterns related to movie popularity, revenue generation, audience ratings, and genre trends. The dataset contains multiple attributes such as movie titles, genres, directors, runtime, ratings, budgets, and box office collections.

The goal of this project is to convert raw movie data into **meaningful insights** using data cleaning techniques, pivot table analysis, and interactive Excel dashboards.

Through this project, the following objectives were explored:

- Identify which genres perform best in terms of popularity and revenue  
- Study rating patterns across different years  
- Analyze how production investment influences box office revenue  
- Find the top performing movies and directors  
- Understand overall growth patterns in the entertainment industry  

The final outcome is a **visual dashboard** that summarizes key statistics and allows users to easily interpret movie industry data.

---

# 3. Project Files

### Raw Data
- **Movies.csv** – Original dataset before any processing.

### Processed Data
- **Cleaned_Movies_Dataset.xlsx** – Dataset after preprocessing and formatting.

### Pivot Analysis
- **Movies_pivot_analysis1.xlsx** – Pivot tables used for generating insights.
- **Movies_pivot_analysis2.xlsx** – Additional pivot calculations for dashboard metrics.

### Dashboard
- **Dashboard_image.png** – Screenshot of the final Excel dashboard.

---

# 4. Dataset Information (Data Dictionary)

Below is a description of the variables included in the dataset.

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| id | Integer | Unique identifier assigned to each content item |
| title | Text | Name of the movie or TV show |
| content_type | Text | Category of the content (Movie, TV Series, etc.) |
| genre_primary | Text | Primary genre classification |
| genre_secondary | Text | Additional genre classification if applicable |
| release_year | Integer | Year when the content was released |
| duration_minutes | Integer | Total runtime in minutes |
| rating | Text | Certification rating (PG, R, TV-MA etc.) |
| language | Text | Main language used in the content |
| country_of_origin | Text | Country where the content was produced |
| imdb_rating | Decimal | IMDb rating score ranging from 0 to 10 |
| production_budget | Decimal | Budget used to produce the content |
| box_office_revenue | Decimal | Total box office revenue generated |
| number_of_seasons | Integer | Number of seasons (for TV series) |
| number_of_episodes | Integer | Total episode count (for TV series) |
| is_netflix_original | Boolean | Indicates if the content is a Netflix original |
| added_to_platform | Date | Date when the content was added to the platform |
| content_warning | Boolean | Indicates presence of a content warning |

---

# 5. Data Cleaning Steps

Several preprocessing steps were performed to prepare the dataset for analysis.

- The **movie_id** column originally contained values such as *movie_001*.  
- The numeric portion of the ID was extracted for easier handling.  
- The original ID format column was removed after extraction.  
- The dataset was sorted to maintain better structure and readability.  
- Column headers were reviewed and standardized for consistency.  

No complex transformations were required since the dataset was relatively clean.

---

# 6. Dashboard Insights

The Excel dashboard summarizes multiple important metrics including:

- Total number of content items  
- Average runtime of content  
- Average IMDb rating  
- Total production investment  
- Total box office earnings  
- Total seasons and episodes for TV series  

### Visualizations Included

The dashboard contains the following visual analyses:

- Content distribution by type  
- Runtime comparison across content types  
- Average rating comparison by content category  
- Investment vs Return analysis (Budget vs Revenue)  
- Country-wise financial comparison  
- Global map showing content distribution by country  

These visualizations help in understanding both **content trends and financial performance**.

---

# 7. Dashboard Preview

![Dashboard Preview](Dashboard_image.png)

---

# 8. Key Findings

The analysis reveals several important patterns in the dataset.

Movies represent the largest share of total content available in the dataset. They also account for the majority of production spending and overall box office revenue.

The **investment versus return analysis** indicates that movies generally produce higher financial returns compared to other content formats.

TV series contribute significantly through their larger number of seasons and episodes, reflecting long-term viewer engagement.

Average IMDb ratings appear relatively stable across different content types, suggesting similar audience reception levels.

From a geographical perspective, the **United States dominates both production spending and revenue generation**, while countries like the United Kingdom, South Korea, and India also contribute notable content.

---

# 9. Final Conclusion

This project demonstrates how data analysis and visualization techniques can transform raw entertainment data into useful insights.

The results highlight that movies dominate the industry in terms of revenue and production investment, while television series maintain strong engagement through multiple seasons and episodes.

The relationship between **production budget and box office revenue** suggests that higher investments often lead to higher financial returns.

Country-wise insights also show the strong influence of the United States in global content production.

Overall, the dashboard provides a clear overview of content trends, financial performance, and global distribution patterns within the entertainment industry.
