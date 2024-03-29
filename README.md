## Turkey Student Evaluation

### Problem
The problem statement is a typical unsupervised learning problem, where with a given
dataset we need to find patterns or groupings in the data without any labeled output
variable.

### About Dataset
In this case, the dataset consists of feedback from students who attended multiple courses
at Gazi University, Ankara. Each feedback consists of evaluation questions and various
other attributes, such as attendance, difficulty. The series of questions which includes
course structure, level and quality of delivery, clarity of course objectives, course difficulty,
course impact on student’s overall college experience and goals, course
relevance, and aspects such as willingness and ability, and preferences are answered by the
students. There are 28 questions, each answered from 1 (very bad) to 5 (very good).

### Attribute Information:
- instr: Instructor’s identifier; values taken from {1,2,3}
- class: Course code (descriptor); values taken from {1-13}
- repeat: Number of times the student is taking this course; values taken from {0,1,2,3}
- attendance: Code of the level of attendance; values from {0, 1, 2, 3, 4}
- difficulty: Level of difficulty of the course as perceived by the student; values taken from {1,2,3,4,5}
- Q1: The semester course content, teaching method and evaluation system were provided at the start.
- Q2: The course aims and objectives were clearly stated at the beginning of the period.
- Q3: The course was worth the amount of credit assigned to it.
- Q4: The course was taught according to the syllabus announced on the first day of class.
- Q5: The class discussions, homework assignments, applications and studies were satisfactory.
- Q6: The textbook and other courses resources were sufficient and up to date.
- Q7: The course allowed field work, applications, laboratory, discussion and other studies.
- Q8: The quizzes, assignments, projects and exams contributed to helping the learning.
- Q9: I greatly enjoyed the class and was eager to actively participate during the lectures.
- Q10: My initial expectations about the course were met at the end of the period or year.
- Q11: The course was relevant and beneficial to my professional development.
- Q12: The course helped me look at life and the world with a new perspective.
- Q13: The Instructor’s knowledge was relevant and up to date.
- Q14: The Instructor came prepared for classes.
- Q15: The Instructor taught in accordance with the announced lesson plan.
- Q16: The Instructor was committed to the course and was understandable.
- Q17: The Instructor arrived on time for classes.
- Q18: The Instructor has a smooth and easy to follow delivery/speech.
- Q19: The Instructor made effective use of class hours.
- Q20: The Instructor explained the course and was eager to be helpful to students.
- Q21: The Instructor demonstrated a positive approach to students.
- Q22: The Instructor was open and respectful of the views of students about the course.
- Q23: The Instructor encouraged participation in the course.
- Q24: The Instructor gave relevant homework assignments/projects, and helped/guided students.
- Q25: The Instructor responded to questions about the course inside and outside of the course.
- Q26: The Instructor’s evaluation system (midterm and final questions, projects, assignments, etc.) effectively measured the course objectives.
- Q27: The Instructor provided solutions to exams and discussed them with students.
- Q28: The Instructor treated all students in a right and objective manner.
- Q1-Q28 are all Likert-type, meaning that the values are taken from {1,2,3,4,5}
