 # Coursera Course Analysis Project

## Project Overview
This project analyzes a Coursera dataset to uncover insights into course ratings, student enrollments, course difficulty, and the organizations offering these courses. The objective is to explore the distribution of key variables, examine relationships between course features, and identify trends in enrollments and ratings.

## Objectives
- Explore and clean the dataset (missing values, duplicates, and data formats).
- Analyze distributions of `course_students_enrolled`, `course_rating`, and `course_difficulty`.
- Identify top organizations, certificate types, and most popular courses.
- Explore the relationship between course ratings, enrollments, difficulty, and certificate type.
- Conduct statistical tests like Tukey's HSD to compare course ratings across difficulty levels.
- Visualize the results for clearer interpretation.

## Key Findings
- **No Missing Values or Duplicates**: The dataset was clean, with no missing values or duplicates.
- **Top Organizations**: The University of Pennsylvania (59 courses) and University of Michigan (41 courses) are the largest course providers.
- **Enrollment Data**: After converting enrollments to numeric values, we applied the Box-Cox transformation to normalize the skewed data.
- **Certificate Type Distribution**: Most courses are labeled as "COURSE" (65.3%), with fewer "SPECIALIZATION" (33.3%) and "PROFESSIONAL CERTIFICATE" (1.3%).
- **Course Difficulty**: The majority of courses are categorized as "BEGINNER" (487 courses), with "INTERMEDIATE" (198 courses) and "MIXED" (187 courses).
- **Most Popular Courses**: "Machine Learning" leads with 3.49M enrollments, followed by "The Science of Well-Being" and "Python for Everybody".
- **Outliers**: 10 outliers were found in student enrollments but were retained as they appeared reasonable.
- **Course Rating Distribution**: The majority of courses have ratings between 4.6 and 4.8, with few ratings reaching 4.9.
- **Course Difficulty vs. Rating**: "MIXED" courses had the highest average rating (4.71), while "ADVANCED" had the lowest (4.60).
- **Correlation**: A weak positive correlation (0.07) was found between course ratings and student enrollments.

## Project Summary & Future Improvements
The analysis provides valuable insights into Coursera courses, but there are opportunities for improvement:
- **Additional Features**: Incorporating course duration, content, or instructor data would enhance the analysis.
- **Predictive Models**: Future work could include predictive modeling for course ratings or enrollments.
- **Data Quality**: Further refinement in data cleaning and feature engineering could improve the analysis.

## Conclusion
This project successfully analyzed the relationship between course ratings, enrollments, difficulty levels, and certificate types. While course difficulty impacts ratings, the weak correlation with enrollments suggests other factors, like content or marketing, may play a larger role. This analysis serves as a foundation for understanding online learning platforms like Coursera.
