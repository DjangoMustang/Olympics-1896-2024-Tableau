# Olympics-1896-2024-Tableau
Complete history of Olympic winners only (countries and athletes) form 1896 to 2024, summer and winter games included.
Here's a draft of the README file for your GitHub project:

---

# Olympic History Dashboard (1896 - 2024)

## Overview
This project visualizes the history of the Summer and Winter Olympics from 1896 to 2024 using Tableau. The dataset includes only winning athletes and countries, with various visualizations showcasing key insights into Olympic medal winners over time. Data has been meticulously cleaned and merged from two sources: one containing historical data until 2022 and another including forecasted data for 2024.

## Datasets
- **df_medal**: Contains Olympic data from 1896 to 2022.
- **df_medal_24**: Contains Olympic data for 2024.
- Data only includes **winning athletes** and **country names** (no non-medal participants).
  
The cleaned and merged dataset is available as a final Excel file, which was used to create the visualizations.

## Visualizations & Features

### 1. **World Map**
- **Plot**: Countries where the Olympics have been held.
- **Highlight**: Number of participating countries (only winners).

### 2. **Country and Medal Count Table**
- **Data**: Countries with their corresponding total medal counts.
- **Metric**: Medal tally (Gold, Silver, Bronze).

### 3. **Bar Chart**
- **Display**: Winning athletes and their respective countries for each year.
- **Color Hue**: Gender of the athletes (to visually differentiate male and female athletes).
- **X-axis**: Years.
- **Y-axis**: Medal counts and country representation.

### 4. **Medalist Table**
- **Data**: Athlete names and their medal counts (Gold, Silver, Bronze).
- **Filter**: Country filter allows selection of a specific nation to focus on its medal-winning athletes.

### 5. **Country Medal Tally Table**
- **Metric**: Lists countries and their overall performance in terms of total medals won over the years.

### 6. **Top Athletes Table**
- **Display**: The athletes with the most medals across all Olympic games.

### 7. **Top Sports Table**
- **Display**: Sports that have produced the most medal winners, broken down by Gold, Silver, and Bronze.

## Tools & Techniques
- **Tableau**: Used for building the dashboard and creating the visualizations.
- **Data Cleaning**: The datasets required extensive cleaning before merging, which was done in Python and uploaded on Kaggle.
- **Kaggle**: The Python code and dataset cleaning process are stored in the Kaggle notebook. https://www.kaggle.com/code/djangomustang/olympics-summer-winter-1896-2022

## How to Use
1. Clone the repository.
2. Access the final Excel dataset (`olympics_1896_2024_s_w.xlsx`).
3. Use the Tableau dashboard file to explore various visualizations.
   
   Alternatively, upload the Excel file to your own Tableau environment and recreate or modify the visualizations.

## Future Enhancements
- Adding more athlete-specific metrics (age, event participation) to enhance the analysis.
- Incorporating non-medalist athletes for a complete view of participation.
- Interactive filters for year and event-specific analysis.

## Acknowledgments
- Data was obtained from publicly available sources on the Olympics and curated to focus on medal winners.

---

Let me know if you'd like any revisions!
