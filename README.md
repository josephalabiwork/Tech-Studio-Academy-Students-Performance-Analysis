# Tech-Studio-Academy-Students-Performance-Analysis
## This analysis was performed using power bi

### Introduction
This dataset captures student engagement, learning activities, and performance across academic programs and learning modes. It allows analysis of how attendance, participation, satisfaction, and internships relate to final performance and course completion, supporting insights into factors that drive student success.

### Business Understanding
Student performance and retention are critical indicators of the effectiveness of training programs. High dropout rates or low performance can negatively impact the institution’s reputation and student satisfaction.
This project seeks to answer:
*	Which course shows the highest student engagement level?
*	Is there any relationship between engagement level and final grade?
*	Do onsite learners perform better than online learners?
*	Which city has students with the best completion rates?
*	How does the number of mentorship sessions affect satisfaction or performance?
*	What can Tech Studio Academy improve to boost student success and engagement?
### Data Understanding
Dataset Overview
The dataset contains student demographic and engagement attributes:
Column Name
* Student_ID   -                       Unique identifier for each student
* Name          -                      Student name
* Gender       -                       Male/Female
* Age          -                       Age of student
* City           -                     Location of residence
* Program          -                    Type of academic program enrolled
* Learning_Mode      -                  Online or Onsite learning
* Attendance_Rate (%)     -             Percentage class attendance
* Participation_Score     -              Engagement in class activities (Scale 1–10)
* Internship_Sessions    -               Number of internship practical sessions attended
* Satisfaction_Score     -               Student satisfaction with the learning experience (Scale 1–10)
* Final_Grade (%)        -               Final academic score
* Completion_Status      -               Completed or Dropped out
* Year                   -               Academic session year

*  All metrics are intended to provide insights into student engagement and its relationship with performance outcomes.

 ### General Observations
	*	Higher attendance and participation generally align with higher final grades.
	*	Students with lower satisfaction scores tend to have lower performance outcomes.
	*	Dropped-out students show consistently lower engagent metrics.
    *   With a final grade of 97, Samuel was the top-performing student. His high engagement level, participation, and satisfaction scores contributed to his outstanding performance
    *   Lagos had the highest registered students
    *   Abuja achieved the highest completion rate, with all registered students successfully finishing their courses.
    *   Onsite students did better than online students

### Key Insights
#### Student Engagement Strongly Predicts Performance
The correlation matrix shows very strong positive relationships between:
	* Attendance Rate and Final Grade (correlation ≈ 0.97)
	* Participation Score and Final Grade (correlation ≈ 0.98)
	•* Internship Sessions and Final Grade (correlation ≈ 0.90)
* This means students who attend classes regularly, engage actively, and complete more internship sessions consistently score higher.
#### Satisfaction is Linked to Better Outcomes
Satisfaction Score has a strong positive relationship with final grades (correlation ≈ 0.94).
Students who feel more satisfied with the learning experience perform better academically and are more likely to complete their program.
#### Dropout Students Show Noticeably Lower Engagement
Students marked as Dropped have:
	* Attendance typically below 70% in most cases
	* Participation scores of 6 or lower
	* Fewer internship sessions
This confirms that disengagement is a strong predictor of dropping out.
#### Onsite Students Tend to Have Higher Performance and Satisfaction
Although not explicitly numerical in correlation, the dataset suggests onsite learners generally have slightly:
	* Higher attendance
	* Higher satisfaction
	* Higher final grades
Increased face-to-face interaction may contribute to stronger learning outcomes.
#### Internship Participation is a Major Skill Impact Factor
Students with 4 or more internship sessions consistently score higher (final grades above 80%).
Practical exposure reinforces learning effectiveness.

### Recommendations
#### Encourage Consistent Attendance and Participation
* Since engagement strongly predicts performance, implement strategies such as attendance monitoring, participation incentives, and interactive class activities to keep students involved.
#### Enhance Student Satisfaction
* Gather regular feedback on courses and learning experiences. Address concerns promptly to maintain high satisfaction, which is linked to better performance and completion rates.
#### Support At-Risk Students
* identify students with low attendance, participation, or internship involvement early. Provide mentorship, counseling, or targeted interventions to reduce dropout risk.
#### Promote Onsite or Hybrid Learning Opportunities
* Given that onsite learners show slightly higher performance and satisfaction, consider incorporating more face-to-face interactions, practical sessions, or hybrid learning components where feasible.
#### Expand Internship and Practical Experience
* Encourage students to participate in multiple internship sessions or practical projects. Hands-on experience reinforces learning and significantly improves final grades.
#### Leverage Best Practices from High-Performing Regions
* Analyze Abuja’s approach to achieve a 100% completion rate and apply similar strategies to other locations.
#### Recognize and Reward Top Performers
* Highlight achievements of students like Samuel to motivate peers and reinforce the value of engagement, participation, and satisfaction in academic success.

### Conclusion
* The analysis of the student dataset highlights the strong impact of engagement, satisfaction, and practical experience on academic performance and course completion. Key findings include:
Engagement Matters: Higher attendance, participation, and internship involvement consistently correlate with better final grades and completion rates.
* Satisfaction Drives Success:   Students who report higher satisfaction with their courses tend to perform better academically and are more likely to complete their programs.
* Early Intervention is Critical: Students with low engagement metrics are at higher risk of dropping out, emphasizing the need for timely support and mentoring.
* Regional and Mode Differences: Abuja achieved the highest completion rate, while onsite learners generally outperform online learners, suggesting benefits from face-to-face interaction and structured learning environments.
* Practical Experience is Valuable: Participation in internships reinforces learning, improving performance and readiness for professional opportunities.
* Top Performers Set Benchmarks: Exemplary students, such as Samuel, demonstrate how high engagement, participation, and satisfaction translate into academic excellence.
* Overall, the dataset underscores the importance of fostering engagement, satisfaction, and practical learning opportunities to enhance student outcomes. These insights can guide educators, administrators, and policymakers in designing interventions and programs that maximize student success.

