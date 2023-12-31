# CSCI 2897: Calculating Biological Quantities (Fall 2023)

__Prof. [Stephen Kissler](mailto:stephen.kissler@colorado.edu)__ 
([ECES 118D](Images/ECCRmap.png))\
Tu/Th 2:30 - 3:45 \
JSCBB B115 \
Office hours: TBD (fill out poll [here](http://whenisgood.net/pc8ydjw))


## Schedule

| Date      | Topic                                                         | Reading       | Links                                                                                 | Assignments                  |
| --------- | ------------------------------------------------------------- | ------------- | ------------------------------------------------------------------------------------- | ---------------------------- |
| 8/29      | Syllabus & why are we here?                                   |               | Lec. 1                                                                                |                              |
| 8/31      | How to Construct a Model                                      | OD-1          | Lec. 2                                                                                | A0 Due  (9/1)                |
| 9/5       | Difference equation models: generating and solving            | review OD-2   | Lec. 3                                                                                |                              |
| 9/7       | Stability of nonlinear difference equations; chaos            | OD-3.1,3.2    | Lec. 4                                                                                |                              |
| 9/12      | Systems of equations and introduction to matrices             | OD-3.2        | Lec. 5                                                                                |                              |
| 9/14      | Matrices as operators: eigenvalues and eigenvectors           | Z-2.2         | Lec. 6                                                                                | A1 Due (9/15)                |
| 9/19      | Solving matrix equations using the inverse; special topics    | OD-3.3        | Lec. 7                                                                                |                              |
| 9/21\*    | _Catch up_                                                    |               |                                                                                       |                              |
| 9/26      | Introduction to ODEs: analytic vs. numeric solutions          | OD-3.4        | Lec. 8                                                                                |                              |
| 9/28      | Fundamental ODE models and their features                     | OD-3.4        | Lec. 9                                                                                | A2 Due (9/29)                |
| 10/3\*    | Analytic and asymptotic analysis of fundamental ODE models    |               | Lec. 10                                                                               |                              |
| 10/5      | Competition models: standard and Lotka-Volterra               |               | Lec. 11                                                                               |                              |
| 10/10     | Stability of multi-variate competition equations              |               | Lec. 12                                                                               |                              |
| 10/12     | _Catch up/review_                                             |               |                                                                                       | A3 Due (10/13)               |
| 10/17     | __MIDTERM__                                                   |               |                                                                                       |                              |
| 10/19     | Introduction to epidemic modeling                             |               | Lec. 13                                                                               |                              |
| 10/24     | Extending epidemic models                                     |               | Lec. 14                                                                               |                              |
| 10/26     | Age-structured epidemics                                      |               | Lec. 15                                                                               | Project Proposal Due (10/27) |
| 10/31     | Spatially structured epidemics                                |               | Lec. 16                                                                               |                              |
| 11/2      | Modeling evolution: an introduction to game theory            |               | Lec. 17                                                                               |                              |
| 11/7      | Modeling evolution: cooperation                               |               | Lec. 18                                                                               |                              |
| 11/9      | Modeling evolution: relationships                             |               | Lec. 19                                                                               | A4 Due (11/10)               |
| 11/14     | Simluating evolutionary games                                 |               | Lec. 20                                                                               |                              |
| 11/16     | _Catch up_                                                    |               |                                                                                       |                              |
| 11/21     | FALL BREAK                                                    |               |                                                                                       |                              |
| 11/23     | FALL BREAK                                                    |               |                                                                                       |                              |
| 11/28\*   | Combining evolutionary and population dynamics (forward sims) |               | Lec. 21                                                                               |                              |
| 11/30\*   | Combining evolutionary and population dynamics (inference)    |               | Lec. 22                                                                               | A5 Due (12/1)                |
| 12/5      | Interim project presentations (Last names A-K)                |               |                                                                                       |                              |
| 12/7      | Interim project presentations (Last names L-Z)                |               |                                                                                       |                              |
| 12/12     | Work on your project                                          |               |                                                                                       |                              |
| 12/14     | Work on your project                                          |               |                                                                                       |                              |
| final day | __Project Report Due__                                        |               |                                                                                       |                              |

\* Indicates a possibly virtual class session 

## Syllabus
Course: CSCI 2897  
Lectures: Tuesday & Thursday, 2:00pm – 3:15pm  
Location: JSCBB B115  
Lecturer: Prof. Stephen Kissler 
Office Hours: TBD
Email: stephen.kissler@colorado.edu  
Webpage: [https://github.com/skissler/CBQ2023](https://github.com/skissler/CBQ2023) 

### Description
*Calculating Biological Quantities* is an interdisciplinary course that brings together mathematics, coding, modeling, and biology. It is part of CU Boulder's *Computational Biology* minor.  Our **learning goals** in this course include:

* Mastering practical mathematical techniques for representing and analyzing biological quantities of different kinds
* Developing mathematical intuition about common biological calculations and concepts
* Learning to model biologically related feedback processes, and solve or analyze their corresponding differential or difference equations
* Adapting and combining methods to solve biological problems
* Gaining confidence in decoding mathematical models and language, including the ideas and vocabulary of differential equations and linear algebra

### Prerequisites
MATH 1300 or APPM 1350 (Calc I).  This course has its roots in biology, math, and computer science, and while knowledge of all three is great, the whole point of the class is to develop strengths in the interdisciplinary space *between* these three fields. If you are enrolled in the course and feel that one area or another is a problem, let's talk about it. 

### Texts 
* [Required] Otto & Day: *A Biologist's Guide to Mathematical Modeling in Ecology and Evolution*
* [Required] Zill: *A First Course in Differential Equations*

Both of these texts are freely available online through the University of Colorado Library. 

### Overview
* This is a mostly lecture-style class, in which I write on blank-ish slides and we talk about problems. 
* Readings may be assigned before class. 
* Problem sets consist of a mix of pen-and-paper and coding-type exercises. 
* A course project will allow students to engage with the course material over a longer period than homeworks. There are three components that will be graded: a Proposal, a Presentation, and a Report. 


### Coursework & Grading
* **Grade Breakdown:** This course will be scored on a points-based system out of 300 total points, divided as follows: 

	- Homework: 100 points (20 per assignment with six assignments, one of which will be dropped - see below)
	- Midterm: 40 points
	- Project proposal: 40 points 
	- Project presentation: 20 points 
	- Project report: 100 points 

Letter grades will be assigned at the end of the course based on percent score out of 300, with A=90%+, B=80%-89%, C=70%-79%, D=60%-69%, F=<60%.   
* **Schedule:** The course consists of a "methods" section (prior to the midterm) and an "applications" section (after the midterm). There will be six assignments. Due dates are listed in the schedule above, but may vary due to partial reordering of the course material based on student feedback. The midterm is on 10/17. On 10/27, a project proposal is due. During the second-to-last full week of class, there will be project presentations during which students can get feedback on their in-progress project. The project report will be due at the end of our scheduled "final" slot on __Wed 20 Dec at 7pm.__
* **Exams:** There is one midterm exam. It is worth an equivalent number of points as two homework assignments, and the length and difficulty of the exam will reflect this. The aim of the exam is to provide an opportunity to consolidate the "methods" section of the course before moving on to the "applications" section. 
* **Assignments:** Assignments will consist of a mixture of math (e.g. solve this problem), writing (e.g. explain how X works in a few sentences), and coding (e.g. implement code for this model and produce a plot). Format for solutions will depend on the type of problems, but could include scans (use an [app](https://apps.apple.com/us/app/adobe-scan-pdf-ocr-scanner/id1199564834)!) for handwritten math, PDFs for written explanations, or Jupyter Notebooks for coding problems. Assignments will be submitted via Canvas.
* **Late / Dropped Assignments:** Life happens! Privacy is important! You don't need to ask for a homework to be dropped or to turn something in. Instead: (1) your lowest homework grade will be automatically dropped at the end of the semester. (2) You get three "late days" to use as you wish. You could, for example, turn in one homework 3 days late, or you could turn in three homeworks 1 day late each. Use wisely! Any late turn-ins are rounded up to the nearest whole day, e.g. turning in 5 minutes late or 23 hours late would both count as one day. 
* **Collaboration Policy:** Don't Google, StackOverflow, buy the teacher's edition of the books, or buy Chegg. Instead, work together. *Collaboration is encouraged* on the problem sets. However, you may not copy (in any way) from your collaborators and you must respect University academic policies at all times. To be clear: you may discuss the problems verbally, but you must write up your solutions separately. If you do discuss the problems with someone (and you are encouraged to!), you must then list and describe the extent of your collaboration in your solutions (a footnote is fine). 
* If you're unsure about anything above, please ask ahead of time.

### Course Project

There are three components of the course project to be graded:

1. A project proposal.
2. A short presentation of the key ideas and preliminary results.
3. A 5-page project report, due on the day of the "Final."

* The **goal** of the course project if for students to explore one of the topics from class more deeply, developing and following their own curiosity in a scholarly way. 
* Students may work individually or with a partner. Expectations for projects done in pairs will be higher. Responsibility for balancing workloads between partners will be left to the students.
* Any topic covered in class, from mathematics to biological applications, is in-bounds. 

*Project Proposal* — Submitted via canvas as a typeset PDF *only*, project proposals should include (0) a title and proposer names, and three paragraphs covering (1) background on the topic, (2) research or scholarly questions, and (3) learning goals and anticipated findings. Finally, proposers should note in a bulleted list (4) the key ways that the proposed project connects with topics from class. 

*Project Presentation* — A 10 minute presentation, delivered in class with slides, should summarize the background and goals of the project, along with the important results found. Presenters should expect to field questions from an engaged audience! Note that there is another week's worth of class time to work on projects after the presentations. _Use the presentation wisely!_ The aim is not to present a fully-formed piece of work, but rather to discuss progress so far, sticking points, things you're hoping to achieve by the time the report is due. This is an opportunity to get my feedback and the feedback of your classmates before writing up the full report! 

*Project Paper* — A 5-page typeset paper, with additional pages for references as needed, submitted as a singled PDF via Canvas. The report should be formatted like a scientific paper, with Introduction, Methods, Results, Discussion, and Bibliography sections, with an optional Appendix section for code. The Bibliography should include appropriate references for your work (primary literature, course materials, websites, source data, methods, etc.).

Advice for how to write any of the sections, or typeset a report, is available at any time during office hours! 

Warning: Do not plagiarize any part of the report. Suspected plagiarism will receive a 0.

### Suggestions: 
Suggestions for improvement are welcome at any time. Any concern about the course should be brought first to my attention. Further recourse is available through the office of the Department Chair or the Graduate Program Advisor, both accessible on the 7th floor of the Engineering Center Office Tower.

## Campus-Level Syllabus Information

### Classroom behavior


Students and faculty are responsible for maintaining an appropriate learning environment in all instructional settings, whether in person, remote, or online. Failure to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation, or political philosophy.

For more information, see the [classroom behavior policy](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior), the [Student Code of Conduct](https://www.colorado.edu/sccr/student-conduct), and the [Office of Institutional Equity and Compliance](https://www.colorado.edu/oiec/).

### Requirements for infectious diseases

Members of the CU Boulder community and visitors to campus must follow university, department, and building health and safety requirements and all public health orders to reduce the risk of spreading infectious diseases. 

The CU Boulder campus is currently mask optional. However, if masks are again required in classrooms, students who fail to adhere to masking requirements will be asked to leave class. Students who do not leave class when asked or who refuse to comply with these requirements will be referred to Student Conduct & Conflict Resolution. Students who require accommodation because a disability prevents them from fulfilling safety measures related to infectious disease will be asked to follow the steps in the “Accommodation for Disabilities” statement on this syllabus.

For those who feel ill and think you might have COVID-19 or if you have tested positive for COVID-19, please stay home and follow the [further guidance of the Public Health Office](https://www.colorado.edu/healthcenter/coronavirus-updates/symptoms-and-what-do-if-you-feel-sick). For those who have been in close contact with someone who has COVID-19 but do not have any symptoms and have not tested positive for COVID-19, you do not need to stay home. 


### Accommodation for disabilities, temporary medical conditions, and medical isolation

[Disability Services](https://www.colorado.edu/disabilityservices/) determines accommodations based on documented disabilities in the academic environment. If you qualify for accommodations because of a disability, submit your accommodation letter from Disability Services to your faculty member in a timely manner so your needs can be addressed. Contact Disability Services at 303-492-8671 or dsinfo@colorado.edu for further assistance.  

If you have a temporary medical condition or required medical isolation for which you require accommodation, please send the instructor an email to find a mutually acceptable way to accommodate your situation. There is no need to provide any personal medical details beyond what is needed to work out acceptable accommodations. Also see [Temporary Medical Conditions](http://www.colorado.edu/disabilityservices/students/temporary-medical-conditions) on the Disability Services website.


### Preferred Student Names and Pronouns

CU Boulder recognizes that students' legal information doesn't always align with how they identify. Students may update their preferred names and pronouns via the student portal; those preferred names and pronouns are listed on instructors' class rosters. In the absence of such updates, the name that appears on the class roster is the student's legal name.

### Honor Code

All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the [Honor Code](https://www.colorado.edu/sccr/honor-code). Violations of the Honor Code may include but are not limited to: plagiarism (including use of paper writing services or technology [such as essay bots]), cheating, fabrication, lying, bribery, threat, unauthorized access to academic materials, clicker fraud, submitting the same or similar work in more than one course without permission from all course instructors involved, and aiding academic dishonesty. 

All incidents of academic misconduct will be reported to Student Conduct & Conflict Resolution: honor@colorado.edu, 303-492-5550. Students found responsible for violating the [Honor Code](https://www.colorado.edu/sccr/honor-code) will be assigned resolution outcomes from the Student Conduct & Conflict Resolution as well as be subject to academic sanctions from the faculty member. Visit [Honor Code](https://www.colorado.edu/sccr/honor-code) for more information on the academic integrity policy. 


### Sexual Misconduct, Discrimination, Harassment and/or Related Retaliation

CU Boulder is committed to fostering an inclusive and welcoming learning, working, and living environment. University policy prohibits [protected-class](https://www.colorado.edu/oiec/policies/discrimination-harassment-policy/protected-class-definitions) discrimination and harassment, sexual misconduct (harassment, exploitation, and assault), intimate partner violence (dating or domestic violence), stalking, and related retaliation by or against members of our community on- and off-campus. These behaviors harm individuals and our community. The Office of Institutional Equity and Compliance (OIEC) addresses these concerns, and individuals who believe they have been subjected to misconduct can contact OIEC at 303-492-2127 or email cureport@colorado.edu. Information about university policies, [reporting options](https://www.colorado.edu/oiec/reporting-resolutions/making-report), and support resources can be found on the [OIEC website](http://www.colorado.edu/institutionalequity/).

Please know that faculty and graduate instructors have a responsibility to inform OIEC when they are made aware of incidents related to these policies regardless of when or where something occurred. This is to ensure that individuals impacted receive an outreach from OIEC about their options for addressing a concern and the support resources available. To learn more about reporting and support resources for a variety of issues, visit [Don’t Ignore It](https://www.colorado.edu/dontignoreit/).


### Religious Holidays

Campus policy regarding religious observances requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments or required attendance. In this class, if religious observances require you to miss any required assignments beyond the allowable dropped assignments, contact the instructor via email to find an acceptable solution.

See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.

### Mental health and wellness

The University of Colorado Boulder is committed to the well-being of all students. If you are struggling with personal stressors, mental health or substance use concerns that are impacting academic or daily life, please contact [Counseling and Psychiatric Services (CAPS)](https://www.colorado.edu/counseling/) located in C4C or call (303) 492-2277, 24/7. 

Free and unlimited telehealth is also available through [Academic Live Care](https://www.colorado.edu/health/academiclivecare). The Academic Live Care site also provides information about additional wellness services on campus that are available to students.













