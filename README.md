# Student's Performance 


## Dataset Overview

🔍 This Power BI dashboard analyzes the performance of senior students from a **fictional large high school** at the end of their final semester, utilizing a dataset sourced from Kaggle. It examines how various factors, such as absenteeism, study habits, and career aspirations, impact academic outcomes.

🔗: https://www.kaggle.com/datasets/mexwell/student-scores/data


🔍 The dataset comprises 2,000 records and 17 attributes. 


- **id:** Unique identifier assigned to each student (we need this because it is possible that two or more students have the same name).
- **first_name:** The first name of a student.
- **last_name:** The last name of a student.
- **email:** The email address of a student.
- **gender:** The gender of a student.
- **math_score:** The score obtained by a student in the subject of mathematics (0 – 100).
- **history_score:** History score (0 – 100).
- **physics_score:** Physics score (0 – 100).
- **chemistry_score:** Chemistry score (0 – 100).
- **biology_score:** Biology score (0 – 100).
- **english_score:** English score (0 – 100).
- **geography_score:** Geography score (0 – 100).
- **path_time_job:** This indicates whether a student is engaged in a part-time job. Taking a part-time job can have an effect on grades.
- **absence_days:** The total count of days the student was not present in class due to various reasons.
- **extracurricular_activities:** This captures whether a student participates in extracurricular activities. It could include clubs, sports, arts, or other activities outside of regular academic coursework.
- **weekly_self_study_hours:** This represents the number of hours a student spends on self-study each week. It indicates the amount of time the student dedicates to independent learning and studying outside of class.
- **career_aspiration:** This column records the student’s career aspirations or goals for the future. It provides insight into the profession or field the student aims to pursue after completing their education.



## Data Credibility

**Reliable:**  The current dataset is accurate and complete. Regarding bias, while the dataset appears accurate and complete, determining bias requires a deeper understanding of the data collection methods and potential underlying assumptions. Bias can stem from various sources, including sample selection, measurement processes, or inherent stereotypes. Without detailed information on these aspects, it's challenging to conclusively identify or rule out biases.

**Original:** The data was downloaded from Kaggle but was originally sourced from Sling Academy.

**Comprehensive:** Contains all essential information needed to answer key questions.

**Current:** Not up to date, as the last update was on August 15, 2023.

**Cited:** The data is cited because it includes a DOI (Digital Object Identifier) and references Sling Academy as the original source.


## Grading System 

🔗: https://www.slingacademy.com/article/student-scores-sample-data-csv-json-xlsx-xml/

In this project, the dataset's author specifies that the grading system follows the United States' 0–100 scale, with corresponding letter grades:

A: 90–100 (Excellent)

B: 80–89 (Good)

C: 70–79 (Satisfactory or Average)

D: 60–69 (Below Average)

F: 0–59 (Fail)

Based on this clarification, I applied conditional formatting rules and assigned icons to table columns accordingly.


## Research Questions 

1. Is there a significant difference in GPA between male and female students?

2. How does school absence affect a student’s performance?

3. Is there any difference in absenteeism between boys and girls?

4.  Does working a part-time job impact self-study hours and, in turn, GPA?

5. How are weekly self-study hours related to students' GPA?

6. Which subjects show the highest average scores?




## Insights 


**1. Is there a significant difference in GPA between male and female students?**

No, there is no significant difference in GPA between male and female students.

- The KPI visuals show that both males and females have the same average GPA (80.98) and fall within their respective expected performance ranges.
- The tooltip histogram confirms that their GPA distributions are nearly identical across grade categories.

This suggests that gender is not a strong predictor of academic performance; other factors like study habits, absenteeism, and socioeconomic background likely have a greater influence.

![image](https://github.com/user-attachments/assets/56e572f9-a6d9-4c2e-9530-4aebaf83be31)


![image](https://github.com/user-attachments/assets/002d5c0f-11b1-45d6-b981-34c4a7d3bffd)




✅ **Conclusion:** Male and female students perform similarly in terms of GPA.


**2. How does school absence affect a student’s performance?**

Absenteeism has a negative impact on GPA.

- The scatter plot (GPA vs. Absenteeism) clearly shows a downward trend: students with more absences tend to have lower GPAs and to spend less hours on studying.
- The 100% stacked bar chart on absenteeism by gender also highlights that absenteeism varies among students, potentially influencing performance differences.

  
✅ Conclusion: Higher absenteeism correlates with lower academic performance.


![image](https://github.com/user-attachments/assets/45dfcce1-cc49-4ba5-925f-12fba439d490)


**3. Is there any difference in absenteeism between boys and girls?**

Yes, there are some differences in absenteeism between genders.

- The 100% stacked bar chart on absenteeism by gender shows that both males and females have similar absenteeism levels, but there may be slight variations in the distribution.
- However, since GPA is similar between genders, absenteeism differences may not be drastic enough to create performance gaps.

✅ **Conclusion:** There are slight absenteeism differences, but they do not significantly impact gender-based GPA trends.

![image](https://github.com/user-attachments/assets/0e4f1636-d8b4-4d89-93d3-9bb6ba216ce5)


**4. Does working a part-time job impact self-study hours and, in turn, GPA?**

The clustered bar chart suggests that part-time work does not have a major impact on GPA.

- Students with part-time jobs appear to have similar GPA trends as those without jobs, especially when self-study hours are controlled.
- However, time management could be a factor—students balancing work and studies may need to optimize their schedules.

✅ **Conclusion:** Part-time jobs do not significantly impact GPA, but effective time management remains important.


![image](https://github.com/user-attachments/assets/7899c277-c8b6-4d2d-80a3-a1c714ce7aed)


**5. How are weekly self-study hours related to students' GPA?**

More self-study hours are associated with higher GPA.

- The combo chart shows a positive correlation between self-study hours and GPA—students who study more tend to achieve better grades.
- The self-study hours distribution also suggests that most high-achieving students dedicate a consistent amount of study time each week.
  
✅ **Conclusion:** Increased self-study hours contribute to better academic performance.


![image](https://github.com/user-attachments/assets/0f2cc5f1-1010-4b9f-a488-13eafeb5c198)


**6. Which subjects show the highest average scores?**

- The "Avg Course Score" bar chart shows that Math and Physics have the highest average scores.
- Subjects like History and Biology have relatively lower average scores.

✅ **Conclusion:** Students generally perform better in Math and Physics compared to other subjects.

![image](https://github.com/user-attachments/assets/ac971c29-d9e7-42d4-ac4a-01d4015c2d39)


## Final Takeaway

The analysis reveals that **GPA performance is not significantly influenced by gender**, as both males and females have similar academic outcomes. Instead, **key factors like absenteeism and self-study hours play a major role in determining student success**. **Higher absenteeism correlates with lower GPAs, while increased study hours contribute to better performance**. Additionally, **part-time jobs do not significantly impact GPA**, suggesting that students can balance work and academics effectively. Subjects like Math and Physics tend to have higher average scores, while History and Biology show lower performance.

Overall, the dashboard provides valuable insights into student success, emphasizing the importance of consistent study habits and attendance over demographic factors like gender. 



![image](https://github.com/user-attachments/assets/d80fa38e-bef6-499b-bc4d-cba622248c7e)


## Data Processing & Optimization

The dataset was **clean and complete**, with no missing values, duplicates, or nulls. To enhance analysis, several calculated columns were added, including overall GPA, derived as the average across all course columns.

**Absenteeism levels** were defined using a conditional column, categorizing students based on the maximum absenteeism days (10):

- Low Absenteeism: ≤3 days
- Moderate Absenteeism: ≤7 days
- High Absenteeism: >7 days

## Modeling 

To optimize performance, two dimensional tables (Career Aspiration & Gender) were created and merged with the fact table using a common key. This approach reduces redundancy and aligns with best practices for performance optimization.


![image](https://github.com/user-attachments/assets/7d9b66b7-4209-442d-a235-b30e340fe7fe)



## Vizualization 

### Bar Graphs on KPI cards 

The bar graphs provide additional context for the KPI cards. The average GPA performance of males and females was compared against their own expected range, defined by the 25th and 75th percentile benchmarks for each gender.

Key Components:

- Target Min GPA (Left Section): The 25th percentile (lower boundary of expected range).
- Target Range (Middle Section): The expected GPA range (25th–75th percentile).
- Axis Fill (Right Section): The gap between the 75th percentile and the actual average GPA.
- Constant Line: Represents the average GPA for males in the male visual and females in the female visual.

This method ensures a fair comparison, highlighting how each gender performs relative to their own distribution rather than an overall benchmark.



### Bar Graph - Avg Course Score 

For the bar graph showing GPA per course, a separate aggregate table was created instead of unpivoting the original fact table. This prevents an excessive number of rows per student, ensuring a more efficient data structure.



### Tooltip Histogram 

The  custom tooltip enhances the visualization by offering deeper insights into student performance. To categorize student performance visually, a histogram was created using GPA bins based on the U.S. grading system:

- A (90–100): Excellent
- B (80–89): Good
- C (70–79): Satisfactory/Average
- D (60–69): Below Average
- F (0–59): Fail

The bin configuration used 5 bins, aligning with these grading categories. However, due to the dataset’s minimum GPA (59.14) and maximum GPA (96.14), the bins were adjusted to 50-60, 60-70, 70-80, 80-90, and 90-100. The lowest bin (50-60) compensates for the absence of GPAs below 50, ensuring the full range is covered.

### Interactive Student Details Table


To enhance data exploration and usability, a detailed student table was integrated. This table is accessed by clicking the "Press for Student Details" button, which dynamically expands to display comprehensive student information, including:

- GPA & Absenteeism (Days & Levels)
- Weekly Study Hours
- Part-time Job Status
- Extracurricular Activities
- Career Aspirations
- Individual Subject Scores
  
This feature enables users to investigate specific student performance patterns and identify potential factors influencing their academic success. By providing a granular view, stakeholders (educators, advisors, or administrators) can make data-driven decisions tailored to individual student needs.


![image](https://github.com/user-attachments/assets/5b0f15aa-d779-444d-9875-ab0a7e5df5a5)


The icons accompanying the course columns provide a visual representation of student performance.

![image](https://github.com/user-attachments/assets/d2506f60-a95a-43f0-a631-be1e5d379911) Red downward arrow indicates a failing grade. 

![image](https://github.com/user-attachments/assets/6007d2af-9267-47d3-b3e4-73871d4c5b12) Yellow dash signifies below-average performance.

![image](https://github.com/user-attachments/assets/39127b5f-1eff-4957-be12-ff5428a50403) Rightward arrow represents an average score.

![image](https://github.com/user-attachments/assets/b1028179-ab29-4727-8620-b7823d973b5a) Upward diagonal arrow denotes above-average performance but not yet at excellence.

![image](https://github.com/user-attachments/assets/e8b596b7-d850-4455-8f83-1e355a6214da) Green upward arrow highlights an excellent score.





### Top Student Card & Info buttons 

The Top Student card highlights the highest-performing student, while the info buttons with bookmarks allow users to seamlessly explore detailed student performance data based on predefined filters. Together, they enhance usability by providing both a quick snapshot of excellence and an easy way to dive deeper into individual student insights with minimal effort. 


