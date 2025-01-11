---
jupytext:
  formats: ipynb,md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.16.4
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

# PHYS 305 Computational Physics

+++

**Course Website:** https://ua-2025q1-phys305.github.io

**Semester and Year:** Spring 2025  
**Time:** Tuesday & Thursday 12:30--1:45pm  
**Location:** Saguaro Hall, Room 114

+++

## Description of Course

Modern science relies heavily on computational methods and data analysis, in addition to empirical evidence and scientific theory.
PHYS 305 offers a comprehensive introduction to the essential skills needed for computation- and data-driven physics.
This course covers a range of computational and numerical methods, including integration of Ordinary Differential Equations (ODEs) and Partial Differential Equations (PDEs), equipping students with the tools necessary to solve complex problems in upper level physics.
In addition, students will learn modern statistical methods and apply these techniques to physical research.
The curriculum is designed to bridge theoretical concepts with practical applications.
Through a combination of lectures, hands-on exercises, and projects, students will develop a robust understanding of the essential tools and techniques required for modern astrophysical research.

+++

## Course Prerequisites or Co-requisites

(PHYS 105A or ECE 175) and (PHYS 142 or 143 or 162H) and (PHYS 240 or 241 or 261H).
Prerequisite or concurrent registration in MATH 254 (Intro to ODE) or MATH 355 (Analysis of ODE).

This course is a prerequisite for the following courses: PHYS 332, PHYS 426, PHYS 472.

+++

## Instructor and Contact Information

**Instructor:** Chi-kwan Chan  
**Email:** chanc@arizona.edu (please include PHYS305 in the subject line of all emails)  
**Office:** Steward Observatory N332  
**Office Hours:** Wednesday 11am--noon (Steward Observatory N332) or by appointment 

**TA:** TBA  
**Email:** TBA  
**Office:** TBA  
**Office Hours:** TBA

+++

## Course Format and Teaching Methods

Live in person; lectures and hands-on labs.

+++

## Course Objectives

...

+++

## Expected Learning Outcomes

...

+++

## Absence and Class Participation Policy

The UA's policy concerning Class Attendance and Participation is available at: https://catalog.arizona.edu/policy/courses-credit/courses/class-attendance-participation.

The UA policy regarding absences for any sincerely held religious belief, observance or practice will be accommodated where reasonable, http://policy.arizona.edu/human-resources/religious-accommodation-policy.

Absences pre-approved by the UA Dean of Students (or Dean Designee) will be honored.
See: https://deanofstudents.arizona.edu/policies/attendance-policies-and-practices

Participating in the course and attending lectures and other course events are vital to the learning process.
As such, attendance is required at all lectures and discussion section meetings.
Absences may affect a student's final course grade.
If you anticipate being absent, are unexpectedly absent, or are unable to participate in class online activities, please contact me as soon as possible.
To request a disability-related accommodation to this attendance policy, please contact the Disability Resource Center at (520) 621-3268 or disability@arizona.edu.
If you are experiencing unexpected barriers to your success in your courses, the Dean of Students Office is a central support resource for all students and may be helpful.
The Dean of Students Office is located in the Robert L. Nugent Building, room 100, or call 520-621-7057.

+++

## Makeup Policy for Students Who Register Late

Statement on whether students who register after the first class meeting may make up missed assignments/quizzes and the deadline for doing so.

+++

## Course Communications

...

+++

## Required Texts or Readings

...

+++

## Required or Special Materials

...

+++

## Required Extracurricular Activities

...

+++

## Assignments and Examinations: Schedule/Due Dates

...

+++

## Final Examination or Project

...

+++

## Grading Scale and Policies

There are 6 homework assignments and 2 projects in total.
Each homework assignment worth 10 points and each project worth 20 points.

Assessment Categories | Percentage of Final Grade
--- | ---
6 Homework Assignments | 60%
Project I (Mid-Term)   | 20%
Project II (Final)     | 20%
Total                  | 100%

Students are expected to submit their assignments and projects by the specified deadlines.
Requests for extensions must be made prior to the due date.

This course provides regular letter grades (A–E), which are based on a simple point system:
* A: 80–100 points
* B: 70–79.9 points
* C: 60–69.9 points
* D: 50–59.9 points
* E:  0–49.9 points

No scaling will be applied.

**Incomplete (I) or Withdrawal (W):**
Requests for incomplete (I) or withdrawal (W) must be made in accordance with University policy, which is available at https://catalog.arizona.edu/policy/courses-credit/grading/grading-system.

**Dispute of Grade Policy:**
If a student disagrees on his or her grade on a homework assignment or a project, the student must send the instructor a formal request through email to re-evaluate the grade within a week from the time that the student receives the grade.
Because no scaling will be applied in the final grade, the final grade cannot be re-evaluated.
The student is expected to know his or her own performance throughout the course.

+++

## Scheduled Topics/Activities

#  | Week | Tuesday | Thursday
--- | --- | --- | ---
1  | Jan 12–Jan 18 |                                                                 | Overview and the Python programming language
2  | Jan 19–Jan 25 | *Martin Luther King Jr. Day (no class)*                         | Data representation and round-off errors
3  | Jan 26–Feb  1 | Numerical linear algebra                                        | Guess lecture: useful tools (homework)
4  | Feb  2–Feb  8 | Fourier transform and spectral analyses                         | Interpolation and extrapolation
5  | Feb  9–Feb 15 | Numerical and automatic derivatives                             | Numerical integration of functions (homework)
6  | Feb 16–Feb 22 | Root finding                                                    | Optimization
7  | Feb 24–Mar  1 | Data modeling I                                                 | Data modeling II (homework)
8  | Mar  2–Mar  8 | Project I presentations                                         | Project I presentations
9  | Mar  9–Mar 15 | *Spring recess (no class)*                                      | *Spring recess (no class)*
10 | Mar 16–Mar 22 | The C programming language                                      | ODE integrator I: explicit methods
11 | Mar 24–Mar 29 | ODE integrator II: implicit and symplectic methods              | ODE integrator III: boundary value problems (homework)
12 | Mar 30–Apr  5 | Monte Carlo methods I: random numbers and random walk           | Monte Carlo methods II: Ising model
13 | Apr  6–Apr 12 | Monte Carlo methods III: Hopfield network and Boltzmann machine | Parallel computing (homework)
14 | Apr 13–Apr 19 | Numerical PDEs I: properties of PDEs                            | Numerical PDEs II: finite difference and spectral methods
15 | Apr 20–Apr 26 | Numerical PDEs III: finite volume methods                       | Numerical PDEs IV: finite element methods (homework)
16 | Apr 27–May  3 | Project II presentations                                        | Project II presentations
17 | May  4–May 10 | Visiting UA HPC                                                 | *Reading Day (no class)*

+++

## Biography

Prof. Chi-kwan "CK" Chan is a computational astrophysicist working with cutting edge technologies to advance both theoretical and observational research.
He has developed new algorithms to study magnetohydrodynamic turbulence, used graphics processing units (GPUs) to accelerate general relativistic ray tracing, designed cloud computing infrastructures to handle big observational data, and applied machine learning algorithms to speed up and automate data processing.
Some of CK's active projects include simulating and understanding accretion disks, capturing images of black holes, and visualizing astrophysical simulations in virtual reality.
A true wildcat, CK received his bachelors and doctoral degrees from the University of Arizona.

+++

## Classroom Behavior Policy

To foster a positive learning environment, students and instructors have a shared responsibility.
We want a safe, welcoming, and inclusive environment where all of us feel comfortable with each other and where we can challenge ourselves to succeed.
To that end, our focus is on the tasks at hand and not on extraneous activities (e.g., texting, chatting, reading a newspaper, making phone calls, web surfing, etc.).

+++

## Threatening Behavior Policy

The UA Threatening Behavior by Students Policy prohibits threats of physical harm to any member of the University community, including to oneself. See http://policy.arizona.edu/education-and-student-affairs/threatening-behavior-students.

+++

## Accessibility and Accommodations

Recommended language is provided on the Disability Resource Center website: http://drc.arizona.edu/instructors/syllabus-statement.

+++

## Code of Academic Integrity

Students are encouraged to share intellectual views and discuss freely the principles and applications of course materials.
However, graded work/exercises must be the product of independent effort unless otherwise instructed.
Students are expected to adhere to the UA Code of Academic Integrity as described in the UA General Catalog. See:  https://deanofstudents.arizona.edu/student-rights-responsibilities/academic-integrity.

The University Libraries have some excellent tips for avoiding plagiarism, available at https://lib.arizona.edu/research/citing/plagiarism.

Selling class notes and/or other course materials to other students or to a third party for resale is not permitted without the instructor's express written consent.
Violations to this and other course rules are subject to the Code of Academic Integrity and may result in course sanctions.
Additionally, students who use D2L or UA e-mail to sell or buy these copyrighted materials are subject to Code of Conduct Violations for misuse of student e-mail addresses.
This conduct may also constitute copyright infringement.

+++

## Nondiscrimination and Anti-harassment Policy

The University of Arizona is committed to creating and maintaining an environment free of discrimination.
In support of this commitment, the University prohibits discrimination, including harassment and retaliation, based on a protected classification, including race, color, religion, sex (including pregnancy), national origin, age, disability, veteran status, sexual orientation, gender identity, or genetic information.
For more information, including how to report a concern, please see https://policy.arizona.edu/employment-human-resources/nondiscrimination-and-anti-harassment-policy

Our classroom is a place where everyone is encouraged to express well-formed opinions and their reasons for those opinions.
We also want to create a tolerant and open environment where such opinions can be expressed without resorting to bullying or discrimination of others.

+++

## Additional Resources for Students

UA Academic policies and procedures are available at http://catalog.arizona.edu/policies

**Campus Health**  
http://www.health.arizona.edu/  
Campus Health provides quality medical and mental health care services through virtual and in-person care.  
Phone: 520-621-9202

**Counseling and Psych Services (CAPS)**  
https://health.arizona.edu/counseling-psych-services  
CAPS provides mental health care, including short-term counseling services.  
Phone: 520-621-3334

**The Dean of Students Office's Student Assistance Program**  
https://deanofstudents.arizona.edu/support/student-assistance  
Student Assistance helps students manage crises, life traumas, and other barriers that impede success.
The staff addresses the needs of students who experience issues related to social adjustment, academic challenges, psychological health, physical health, victimization, and relationship issues, through a variety of interventions, referrals, and follow up services.  
Email: DOS-deanofstudents@arizona.edu  
Phone: 520-621-7057

**Survivor Advocacy Program**  
https://survivoradvocacy.arizona.edu/  
The Survivor Advocacy Program provides confidential support and advocacy services to student survivors of sexual and gender-based violence.
The Program can also advise students about relevant non-UA resources available within the local community for support.  
Email: survivoradvocacy@arizona.edu  
Phone: 520-621-5767 

+++

## Safety on Campus and in the Classroom

For a list of emergency procedures for all types of incidents, please visit the website of the Critical Incident Response Team (CIRT): https://cirt.arizona.edu/case-emergency/overview

Also watch the video available at https://arizona.sabacloud.com/Saba/Web_spf/NA7P1PRD161/common/learningeventdetail/crtfy000000000003560

+++

## Confidentiality of Student Records

http://www.registrar.arizona.edu/ferpa

+++

## Subject to Change Statement

Information contained in the course syllabus, other than the grade and absence policy, may be subject to change with advance notice, as deemed appropriate by the instructor.

+++

```{tableofcontents}
```
