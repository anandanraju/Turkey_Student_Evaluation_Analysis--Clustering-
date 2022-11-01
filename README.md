# Turkey_Student_Evaluation_Analysis--Clustering-
From this Analysis on Turkey Student Data using KMeans and Hierarchical Clustering Process, We identify the count of Positive, Negative and Neutral values depend on the data provided. Also its value count and dependancy nature on each variable.

![turkey gazi](https://user-images.githubusercontent.com/110320717/199258428-e7a667e9-e1d2-428c-bd10-f09d0867fb15.jpg)

### Attribute Informations:

1.  **Instr**: Instructor's identifier; values taken from {1,2,3} 
2.  **Class**: Course code (descriptor); values taken from {1-13} 
3.  **Repeat**: Number of times the student is taking this course; values taken from {0,1,2,3,...}
4.  **Attendance**: Code of the level of attendance; values from {0, 1, 2, 3, 4}
5.  **Difficulty**: Level of difficulty of the course as perceived by the student; values taken from {1,2,3,4,5}
6.  **Q1**: The semester course content, teaching method and evaluation system were provided at the start.
7.  **Q2**: The course aims and objectives were clearly stated at the beginning of the period.
8.  **Q3**: The course was worth the amount of credit assigned to it.
9.  **Q4**: The course was taught according to the syllabus announced on the first day of class.
10. **Q5**: The class discussions, homework assignments, applications and studies were satisfactory.
11. **Q6**: The textbook and other courses resources were sufficient and up to date.
12. **Q7**: The course allowed field work, applications, laboratory, discussion and other studies.
13. **Q8**: The quizzes, assignments, projects and exams contributed to helping the learning.
14. **Q9**: I greatly enjoyed the class and was eager to actively participate during the lectures.
15. **Q10**: My initial expectations about the course were met at the end of the period or year.
16. **Q11**: The course was relevant and beneficial to my professional development.
17. **Q12**: The course helped me look at life and the world with a new perspective.
18. **Q13**: The Instructor's knowledge was relevant and up to date.
19. **Q14**: The Instructor came prepared for classes.
20. **Q15**: The Instructor taught in accordance with the announced lesson plan.
21. **Q16**: The Instructor was committed to the course and was understandable.
22. **Q17**: The Instructor arrived on time for classes.
23. **Q18**: The Instructor has a smooth and easy to follow delivery/speech.
24. **Q19**: The Instructor made effective use of class hours.
25. **Q20**: The Instructor explained the course and was eager to be helpful to students.
26. **Q21**: The Instructor demonstrated a positive approach to students.
27. **Q22**: The Instructor was open and respectful of the views of students about the course.
28. **Q23**: The Instructor encouraged participation in the course.
29. **Q24**: The Instructor gave relevant homework assignments/projects, and helped/guided students.
30. **Q25**: The Instructor responded to questions about the course inside and outside of the course.
31. **Q26**: The Instructor's evaluation system (midterm and final questions, projects, assignments, etc.) effectively measured the course objectives.
32. **Q27**: The Instructor provided solutions to exams and discussed them with students.
33. **Q28**: The Instructor treated all students in a right and objective manner.

* Q1-Q28 are all Likert-type, meaning that the values are taken from {1,2,3,4,5}

# Table of Contents

1. Import Libraries
2. Checking DataSet
3. Exploratory Data Analysis
4. Correlation Matrix
    * Principal Component Analysis (PCA)
5. Model Training
    * KMeans with PCA-X
    * KMeans with Actual-X
    * Agglomerative Clustering
6. Summary
