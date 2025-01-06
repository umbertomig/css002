# CSS 2 - Data and Modeling in Computational Social Sciences

Syllabus -- Winter 2025

## Course Overview

This course will teach how you to think about **data** and **modeling** for **computational social science**. This will involve raising and examining questions like:

- How is a dataset **formatted**, and is this the appropriate format for what I want to do? 
- Is this dataset **representative** or does it reflect a **biased sample**? 
- What **ethical considerations** should I take into account when obtaining and analyzing data? 
- What kind of **model** is the most appropriate for these data? 
- How do I **design and implement** these models––ranging in complexity from [linear regression](https://en.wikipedia.org/wiki/Linear_regression) to [support vector machines](https://en.wikipedia.org/wiki/Support_vector_machine)? 

These topics will be discussed in the context of **hands-on practice** with real-world datasets in a **Python programming environment**.

## Key Learning Outcomes

This course is designed to give students a range of conceptual and technical tools. By the end of this course, you will be able to:

1. **Collect** and **wrangle** datasets, preparing them for analysis.
1. **Design** and **implement** clear, concise, and accurate visualizations of data.  
1. **Propose** and **test** hypotheses about data using statistical models.  
1. **Construct** statistical models in Python and **interpret** the results. 
1. **Weigh** the pros and cons of different model evaluation metrics.
1. **Identify** and **explain** ethical issues that arise in CSS, along with analytical issues more broadly.    

## Course Logistics

### When/Where?:

- Lecture: MWF 8:00 to 8:50 AM ([Podemos](https://map.concept3d.com/?id=1005#!ct/18312?s/PODEM_Main) 1A18)
- Coding Lab Sections (optional): 
   - Monday, 3:00 to 3:50 AM ([Podemos](https://map.concept3d.com/?id=1005#!ct/18312?s/PODEM_Main) 1A23)
   - Monday, 4:00 to 4:50 AM ([Podemos](https://map.concept3d.com/?id=1005#!ct/18312?s/PODEM_Main) 1A23)

### Instructor

[Dr. Umberto Mignozzetti](https://github.com/umbertomig): Assistant Teaching Professor in Political Science and CSS.

*Communication Expectations*
1.	Most of the communication regarding the class should be done with your TA. They will let me know if you have questions they cannot solve.
2.	I will only respond to emails if forwarded by the TA. If you have any questions, please come by during office hours.
3.	If you have any questions or want to chat about CSS, PoliSci, my research, sports, etc., please sign into my office hours using Calendly.
4.	[My Calendly URL is here](https://calendly.com/umbertomig/office-hours).

### TA

[Luna Bellitto](TBA)


### Office Hours

| Who? | When? | Where? | How to Schedule? |
| ---- | ----- | ------ | ---------------- |
| Umberto Mignozzetti | MoTu 11:00 AM to 12:00 PM | Zoom (or SSB 393) | [Calendly](https://calendly.com/umbertomig/office-hours) |
| Luna Bellitto | TBA | TBA | [Calendly](TBA) |

### Course GitHub

1. You may find the course's GitHub in [here](https://github.com/umbertomig/css002.git).
1. Course website TBA.


## Grading

### Grade Components

Your grade will be determined by four assessments: attendance, coding labs, problem sets, and a final project.

| Grade Component | Percentage of Final Grade |
| --------------- | ------------------------- |
| 21+ Attendance | 5% ((5/21)% each) |
| 7 Coding Labs | 49% (7% each) |
| 3 Problem Sets | 30% (10% each) |
| 1 Final Project| 15% |

[Here you find the assignments due dates](c_Assignments.md).

#### Attendance
Active participation is essential. The main form of participation is showing up. By showing up, you will ensure you are in the right place at the right time. This is mostly enough to guarantee that you will ask great questions and participate further.

Participation is computed using Canvas quizzes. Every week, I will put on the board a pin for the participation quiz of the day. This will start counting since the first day.

You can miss seven classes and still get full participation marks. And because of that, **I will not** manually input your participation.

#### Coding Lab

Labs are intended to give you hands-on programming experience. You will have one lab each week, designed for completion during the TA session.

*Labs are collaborative*

You can (and should!) work with other classmates. In general, programming is often a team sport. You will find that accurate in software engineering and data science. Thus, labs are an excellent opportunity to practice collaboration with others.

*Labs are graded for effort and correctness*

My lab grading method is:

70% x Completion + 30% x Accuracy

Important: No TA sessions during the first week!

#### Problem-Sets

Problem sets are (roughly) bi-weekly (as in one roughly every two weeks) exercises intended to give you more hands-on experience applying course concepts.

*Problem sets are completed independently.*
Unlike labs, problem sets should be completed independently. You can ask the TAs (or me) for help, but each answer should reflect your work.

*Problem sets are graded mostly for correctness.*
Unlike labs, your grade on a problem set will be graded using the following scheme:

30% x Completion + 70% x Accuracy

*Note on auto-grading*

Note that grading will be done using an auto-grader. This software will check your solutions to each problem and determine whether they are correct.

For the auto-grader to work correctly, it's imperative not to edit or delete any notebook cells containing an assert statement.

What does having a problem set, exam, or lab auto-graded mean? Auto-graders are pieces of code that help us determine if you got it right. It comprises public tests (you can see those) and private tests (you cannot see those). Your grade is computed by having the auto-grader score the correctness in the public and private tests. You can only see your final grade once we run the auto-grader. Your code may be working fine, passing the public tests, but your grade might be lowered (even zero-ed sometimes) if you do not do what we ask. To make sure you get a good grade:

1.	If the code asks you to create a variable, create the variable asked.
2.	If the code asks you to assign a particular value or result to a variable, assign the result or value asked for to the variable.
3.	If the code asks you to create a function, create the function asked.
4.	If the code asks you that your function should have a given parameter, don’t forget to have that parameter in it.
5.	If unsure, test the code: read the problem, understand it, and think of tests that should be true if your code is good.

*Pro-tip*: After completing your assignment, restart the DataHub kernel and rerun all the cells (all this will be clear later). This will tell if the code passes all the public tests, which is an excellent start to getting all the private tests correct. Ask Lilly how to do this.

#### Final Project
As part of the course, you must complete a final project.

You can think of the final project as a more extensive, more coherent problem set. You will be graded for correctness (and you should complete it independently). But unlike the problem sets, the questions in this final project will build towards a more significant conclusion––you will produce a small piece of working software and data analysis.

*Goals*
The goal of this final project is to give you hands-on experience modeling and answer data-related questions in Python.

Unlike the other assessments, the final project is intended to be a more coherent exercise.

*The final project is completed independently.*
Again, you can think of this as a more extensive problem set. It'll be graded for correctness, and you should work independently.

### Letter Grades

If you're taking the course for a letter grade, your grade will be determined according to the scale below. 

Note that the number on the **right-hand** side of the range is *not included* in that range: that is, an "A-" ranges from 90% all the way to 92.999999% but does not include 93% (93% is an A).

 <span>Percentage</span>        | <span>Letter Grade</span>
----------------------|----------------
97%+  | A+
93-97%   | A
90-93%   | A-
87-90%   | B+
83-87%   | B
80-83%   | B-
77-80%   | C+
73-77%   | C
70-73%   | C-
60-69%   | D
<60%     | F

### On Rounding 

Note that my policy is *not* to round up grades for two reasons:

1. If rounding is applied selectively (i.e., only to students who ask), it is unfair to other students.  
2. If rounding is applied across the board, it simply redefines the boundary between two letter grades (e.g., making an 89% the cut-off for an A-).


### Late submissions

Students may submit late assignments up to 7 days after the submission deadline. A 25% penalty will be applied (i.e., if you scored 90%, you'd get 67.5% with the late penalty).


## Questions, feedback, and communication

Instructors can be reached in the following ways:

- Office hours.  
- Public question on Piazza.  
- Private message over Piazza.  
- Email. 

The course Piazza can be found here: https://piazza.com/ucsd/winter2024/602

Note that in general, we prefer communication over Piazza as opposed to email. 


## Other Information

### Academic Integrity

Please turn in your own work. While you are encouraged to work together on some assignments (e.g., on [labs](../labs/overview.md)), you should still understand the code you've submitted. Problem sets and final project should be completed independently.

Please review academic integrity policies [here](http://academicintegrity.ucsd.edu). Cheating and plagiarism are unfair to other students and ultimately to yourself, and you will be penalized if caught. Instead, if you're struggling with something, please come to office hours and ask for help! 

### Class Conduct

All of us (instructors + students) should treat others with respect and follow the UC San Diego [Principles of Community](https://ucsd.edu/about/principles.html). This class should be a welcoming and inclusive environment for everyone, regardless of gender, gender identity and expression, sexual orientation, physical appearance, disability, race, or ethnicity. 

Please be considerate and respectful of your fellow classmates (and instructors), refrain from discriminatory language and harassment, and interact with good faith. 


### Help and support
I want to say that we are here for you! The TAs and I are committed to your learning experience, and if you have any questions or concerns, please let us know!

### Syllabus Changing Policy
The syllabus is a plan, not a contract. It is subject to change throughout the semester. However, I will inform you about any changes or adjustments in any part of the syllabus.

### Acknowledgment

This class borrows considerably from Sean Trott’s CSS 2 class. His class design was so great that I am honored in following his footsteps here.


## Schedule of Course Content

[See the schedule here](b_Schedule.md).
