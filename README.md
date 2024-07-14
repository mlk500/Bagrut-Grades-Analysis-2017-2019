# Data Visualization Project: Analyzing High School Academic Performance in Israel

## Introduction
This project focuses on examining the academic performance of high school students across different districts and sectors in Israel for the years 2017, 2018, and 2019. The aim is to explore patterns, trends, and disparities in student performance, considering subjects that were consistently taught across the three years in the participating schools.

## Data
The dataset used in this project is distributed across three CSV files, each corresponding to a specific year (2017, 2018, and 2019). The files share the same structure, comprising 11 columns each, with a minimum of 14,000 rows in each file. The dataset can be accessed through this link: [Bagrut Data](https://www.meida.org.il/11222).

The original dataset was primarily in Hebrew, but for easier handling and comprehension, the column names were translated from Hebrew to English. The columns include:
- 'district': Indicating the district in which the school is located.
- 'sector': Representing the demographic sector.
- 'school_type': Describing the type of the school (כללי, דתי, עצמאי).
- 'school_id': The unique identifier for each school.
- 'school_name': The name of the school.
- 'city': The city where the school is located.
- 'subject': The specific subject being evaluated.
- 'class_of': Year.
- 'units': The number of units for each subject.
- 'number_of_examinees': The number of students examined in each subject.
- 'average_final_grade': The average final grade for each subject per school per year.

An additional CSV file containing geocoding information for Israeli cities was obtained from the Tableau community and incorporated into the dataset.

## Data Pre-processing
The data underwent cleaning and pre-processing steps:
1. Only schools present in all three years were kept to ensure accurate year-over-year comparisons.
2. For each school, only subjects taught consistently over the three-year period were retained.
3. Unnecessary spaces were stripped from the dataset to ensure consistent formatting.
4. The individual datasets for each year were concatenated into a single file.

The resulting dataset contains:
- 305 villages and cities
- 928 unique schools
- 115 unique subjects
- 3 types of school (פיקוח): ['כללי', 'דתי', 'עצמאי']
- 4 sectors: ['ערבי', 'יהודי', 'בדואי', 'דרוזי']
- 9 districts: ['ירושלים', 'דרום', 'תל אביב', 'מרכז', 'חיפה', 'צפון', 'חינוך התישבותי', "מנח'י", 'חרדי']

## Project Overview
The project revolves around creating two dashboards: 'Overview of Performance' and 'Detailed Exploration of Subjects'.

### Dashboard 1: Overview of Academic Performance
This dashboard assesses the variation in average final grades across different factors, including sector, district, and city. It includes graphs such as:
- Trends in Average Final Grades by Sector
- Average Final Grades by District
- Average Final Grades by City
- Percentage of Schools in Each Sector
- Top 5 Schools in Each Sector by Average Final Grade
- Average Grades Across Multi-Sector Cities
  
![Overview of Performance (1)](https://github.com/user-attachments/assets/4be162df-306c-4ec4-a516-33da761140f5)

[Link to Dashboard, the graphs are interactive](https://public.tableau.com/app/profile/malak.yehia8824/viz/OverviewPerformance/OverviewofPerformance)

### Dashboard 2: Detailed Exploration of Subjects
This dashboard focuses on the trends in subject performance and their distribution across different sectors. It includes graphs such as:
- Top/Bottom Performers Subjects by Score Percentage Improvement from 2017 till 2019
- Most Common Subjects by Sector
- Grade Comparison of Essential Subjects Across Sectors
  
![Detailed Exploration of Subjects  (1)](https://github.com/user-attachments/assets/8dc44150-6ea0-4034-acfb-939325080ded)

[Link to Dashboard, the graphs are interactive](https://public.tableau.com/views/DetailedExplorationofSubjects/DetailedExplorationofSubjects?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Key Insights
1. The Jewish sector showed consistent improvement in average final grades over the years, while the Arab sector experienced a slight decline.
2. The districts of Jerusalem and Tel Aviv had the highest average final grades, while the Bedouin and Druze sectors had the lowest.
3. In multi-sector cities, the Jewish sector generally outperformed other sectors.
4. The most significant improvement in subject scores from 2017 to 2019 was observed in the Arts and less common subjects like Geology, while the least improvement was seen in core subjects like Math and English.
5. The most common subjects taught across all sectors were Math, English, and History, while the least common subjects varied by sector.
6. In the comparison of essential subjects, the Jewish sector consistently outperformed other sectors, particularly in English and Math.

## Story: Unlocking the Progress - A Deep Dive into 5 Units of English in Israel

In addition to the dashboards, the project includes a story that focuses on the progress of 5 units of English across different sectors and schools over the years. The story is designed to provide a more in-depth analysis of a specific subject and its performance trends.

The story consists of four main visualizations:

1. **Number of Schools Offering 5 Units of English Over the Years**
   This graph shows the trend in the number of schools offering 5 units of English from 2017 to 2019. It allows us to observe if there has been an increase or decrease in the availability of this advanced level of English education over time.

2. **Number of Schools Offering 5 Units of English by Sector**
   This graph displays the distribution of schools offering 5 units of English across different sectors. It provides insights into which sectors have a higher or lower concentration of schools providing this level of English education.

3. **Average Grade of 5 Units of English by Sector**
   This graph compares the average grades of 5 units of English across different sectors. It helps identify any disparities in performance between sectors and highlights sectors that may be excelling or struggling in this subject.

4. **Top 5 Schools with the Highest Average Grades in 5 Units of English by Sector**
   This graph showcases the top-performing schools in each sector based on their average grades in 5 units of English. It allows us to identify the schools that are leading in English education within their respective sectors.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/edb49ec3-da5f-42be-a4c5-54c079240435" alt="Story 1"></td>
    <td><img src="https://github.com/user-attachments/assets/b557c91f-dad9-4e53-a9f8-513b112a983d" alt="Story 1 (1)"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/e3ea8466-6ce4-454c-ab39-ac3e86e1f2a4" alt="Story 1 (2)"></td>
    <td><img src="https://github.com/user-attachments/assets/28f4cf08-bc8a-4a22-83d4-35db945d4e30" alt="Story 1 (3)"></td>
  </tr>
</table>

[Link to Story](https://public.tableau.com/views/UnlockingtheProgressADeepDiveinto5UnitsofEnglishinIsrael/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

By presenting this story, we aim to provide a more focused and narrative-driven analysis of a specific subject, complementing the broader insights gained from the dashboards. The story highlights the progress, availability, and performance of 5 units of English across different sectors and schools, offering a deeper understanding of the trends and disparities in this advanced level of English education in Israel.

## Conclusion
This data visualization project provides a comprehensive analysis of high school academic performance in Israel, highlighting disparities and trends across sectors, districts, cities, and subjects. The insights gained from this project can be valuable for educators, policymakers, and other stakeholders in understanding and addressing educational challenges and inequalities in Israel.
