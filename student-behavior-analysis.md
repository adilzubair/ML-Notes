# Student Behavior Analysis

## Summary Statistics and Unique Values

### Summary Statistics for Numeric Columns

- The dataset consists of 480 entries.
- The mean number of times students raised their hands in class is approximately 46.77, with a standard deviation of 30.78.
- The average number of times students visited resources is around 54.80, with a standard deviation of 33.08.
- Announcements view averages at 37.92, with a standard deviation of 26.61.
- Discussion participation averages at 43.28, with a standard deviation of 27.64.
- The minimum and maximum values for these metrics vary from 0 to 100, indicating a wide range of engagement levels among students.

### Unique Values for Non-numeric Columns

- There are two genders represented in the dataset.
- The dataset includes students from 14 different nationalities and places of birth.
- There are three educational stages (StageID), ten grades (GradeID), and three sections (SectionID).
- Students are enrolled in 12 different topics.
- There are two semesters recorded.
- The survey was completed by either the father or the mother (Relation).
- Responses to whether the parent answered the survey, their satisfaction with the school, and student absence days each have two unique values.
- Student class performance is categorized into three levels: Low, Middle, and High.

## Analysis Plan

Our exploratory data analysis will include:

1. Visualizing the distribution of key variables such as gender, nationality, stage ID, grade, topic, semester, and class performance.
2. Examining the relationships between engagement metrics and class performance.
3. Investigating how demographic factors relate to engagement metrics and class performance.
4. Assessing the impact of parental involvement on student performance and engagement.

## Distribution of Key Categorical Variables

![Gender Distribution](figures2/img1.jpg)

### Gender Distribution

The gender distribution chart shows the count of male and female students, providing insight into the gender balance within the student population.

### Nationality Distribution

This chart illustrates the diversity of nationalities in the dataset, with rotated x-axis labels for better readability.

### StageID Distribution

The distribution across educational stages is shown, indicating the spread of students across different levels of education.

## Relationships Between Engagement Metrics and Class Performance

![Raised Hands by Class Performance](figures2/img2.jpg)

### Raised Hands by Class Performance

A positive correlation is observed between the frequency of raising hands and class performance levels.

### Visited Resources by Class Performance

Students with high performance visit educational resources more often than their peers.

### Announcements View by Class Performance

Regular viewing of announcements correlates positively with higher class performance.

## Relationships Between Demographic Factors and Engagement Metrics

![Raised Hands by Gender](figures2/img3.jpg)

### Raised Hands by Gender

The engagement through raised hands varies by gender, suggesting differences in participation habits.

### Visited Resources by Gender

One gender may be more inclined to use educational resources than the other.

### Announcements View by Gender

The median viewing of announcements shows differentiation between genders.

## Insights and Conclusions

- Active engagement in class is associated with higher academic performance.
- Gender differences in engagement metrics suggest the need for tailored engagement strategies.
- Educators should consider inclusive strategies to encourage equal participation among all students.
