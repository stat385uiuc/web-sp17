---
title: "Syllabus"
date: "2017-01-17T21:48:51-07:00"
---

# STAT 385: Statistics Programming Methods

#### *University of Illinois at Urbana-Champaign*

#### *Spring 2017*

# Location and Time

- **Location:** Noyes 161
- **Time:** Monday, Wednesday, and Friday, 3:00 PM - 3:50 PM

# Course Websites

* **Discussion Forum:** <https://piazza.com/illinois/spring2017/stat385/home>
* **Source Code Repository:**  <http://github.com/stat385uiuc/sp17>

# Course Staff

### Instructor

- **Name:** Stephane Guerrier
- **Email:** stephane@illinois.edu
- **Office:** 117 Illini Hall
- **Office Hours:** TBA

### Teaching Assistant 

- **Name:** James Balamuta
- **Email:** balamut2@illinois.edu
- **Office:** 117 Illini Hall
- **Office Hours:** TBA

# Course Description

The world is rapidly evolving to rely on data driven decisions. These decisions
come from the work a statistician or data scientist presents in his or her 
reports. In order to present an analysis, the analyst needs to be able to 
leverage computing resources through programming to unearth patterns and models
that exist within data sets. As a result, statisticians and data scientists must
be savvy to programming methods that are useful to the wide variety of analysis
that they will be expected to perform.

For the focus of the course, fundamental programming techniques and 
considerations will be introduced. Students will learn one of the leading
statistical programming languages in depth and will be well positioned to easily
learn others based on general principles. With this in mind, the course provides
a framework for writing statistical algorithms through the creation of functions
and object oriented programming. Students will also create dynamic reports that
encapsulate their code.

# Course Objectives

After completing the course, students should be able to:

- Analyze and discuss the meaning behind lines of code;
- Construct implementations of a statistical algorithm within a statistical 
  computing environment;
- Explain fundamental computing theory as it applies within the domain of 
  Statistics.

# Course Content

Tentative subjects include:

- **Paradigms:** R, C++ (using Rcpp), OpenMP, Bash, git, regex;
- **Reproducible Research:** `knitr`, `rmarkdown`, and `packrat`;
- **Computing Theory:** Control logic, scoping logic, big O, data structures, object-oriented programming;
- **Algorithms:** SLR, MLR, ANOVA, Accept-Reject, Probability Integral Transform;
- **R packages:** Construction of R-packages using `devtools`, `roxygen2`, `profvis`, and `testthat`;
- **Visualizations:** Exploratory Data Analysis with Base R and `ggplot2`.

# Textbooks

Please note that these textbooks are legally available online for free.
If you wish to purchase a paper copy, you are more than welcome to obtain one. 
However, the references throughout the course will be primarily based upon
the electronic versions.

The following texts will be heavily referenced:

- **Required:** [Advanced R Programming](http://adv-r.had.co.nz/) Hadley Wickham
- **Required:** [R for Data Science](http://r4ds.had.co.nz/) Garrett Grolemund and Hadley Wickham
- **Required:** [The R Inferno](http://www.burns-stat.com/pages/Tutor/R_inferno.pdf) Patrick Burns

The following textbooks are *helpful*, but not necessary to succeed in the course:

- **Supplemental:** [Introduction to Scientific Programming and Simulation Using R](http://www.ms.unimelb.edu.au/~odj/Teaching/MAST30025/spuRs_reformatted_part1.pdf) Owen Jones, Robert Maillardet, and Andrew Robinson
- **Supplemental:** [An introduction to R](https://cran.r-project.org/doc/manuals/R-intro.pdf) Jeffrey Dean and Sanjay Ghemawat
- **Supplemental:** [The Art of R Programming](http://vufind.carli.illinois.edu/vf-uiu/Record/uiu_6955421) Norman Matloff
- **Supplemental:** [R Packages](http://r-pkgs.had.co.nz/) Hadley Wickham
- **Supplemental:** [ggplot2: Elegant Graphics for Data Analysis [2nd Edition - GitHub Only]](https://github.com/hadley/ggplot2-book) Hadley Wickham

# Prerequisites

Prior to taking this course, one should have acquired the following knowledge:

* [STAT 200: Statistical Analysis](http://catalog.illinois.edu/courses-of-instruction/stat/)
* Ability to collaborate in a group project
    * Listen, provide *constructive* dialog, contribute work
* Motivation

**Note:** If you have taken a higher-level course, e.g. STAT 400 or STAT 425, 
this satisfies the STAT 200 requirement.

# Email Policy

All questions related to this class should be asked on piazza except for private
issues (e.g. missing exams). Note that posting anonymous questions on
piazza is not **allowed**.

All course emails must contain in the subject line `[STAT 385]` followed by
a description of the e-mail's contents and should be sent from an 
`@illinois.edu` email address. Failure to adhere to this policy
will either result in:

1. An automated message as a reminder of this policy; 
2. **The email is ignored.**

# Bug Bounty Program

> "To err is human, but to really foul things up you need a computer." 
>
> --- **Paul R. Ehrlich**

The course staff is a *human*. As a result, they will sometimes introduce *bugs*
as material becomes transcribed into a computer. Though, the course staff will 
try their very best to minimize the amount of *bugs* in the course material. 
If he does create a *bug*, please let him know. Depending on the severity, you 
will be compensated with:

* Severe: Unintentionally, part of the code is fundamentally flawed.
    * Fix and/or patch is *required*.
    * **Reward:** Bug Hall of Fame and 1 E.C. point
* Medium: Logical flaws that occur during class.
    * Must explain the flaw and a potential solution
    * **Reward:** Large candy bar of your choice
* Trivial: Typos and Grammar
    * Minor nuisances that if corrected via a pull request will be appreciated. 
    * **Reward:** For every 20 typos and grammar bits a large candy bar of your choice

As an added plus, there are many good discussions that arise due to mistakes...

# Attendence

You are expected to attend all lectures. Each lecture will have its own
magic word that you are responsible for entering into a form link that will be 
provided on piazza. In order to be eligible to receive attendance points, you
must be _in class_, enter the magic word within 5 minutes after it is given, 
and stay for entire duration of class. Periodically, checks will be performed to
verify the attendance. Students who have entered the magic word but are not 
present, will fail class and will have an academic integrity
violation opened against them. Please note, every student is eligible to miss 
*four* class periods without needing to provide a reason. Any known or potential
extracurricular conflicts should be discussed in person with the instructor 
during the first week of classes, or as soon as they arise. Please be proactive.

The exact method that we will use to calculate attendance at the end of the
semester is given by:

```r
my_attendence = function(N, N_max){
    round( min( c( 1, N/(N_max - 4) ) )*100, 2)
}
```

where `N` denotes the number of times a student has attended class and `N_max` 
denotes the maximum number of classes where attendence was taken.

# Exercises

There will be _no_ formal homework assignments this semester. Instead, there 
will be  **five** to **eight** different excerise sets that will be made 
available throughout the semester that students are highly encouraged to do. 
Please note, that the exercises are done without a solution key being
made available.

# Exams

There are **two** exams for this course. The first exam is a midterm that is 
worth **20%** and the second exam is a final exam worth **25%** that takes
place at 8:00-11:00 a.m. on Monday, May 8. The midterm and final exam _may_ have
a take-home portion in addition to a traditional in class examination. 
In such cases, the take-home portion would be due within 24-48 hours after the
start of the exam. The take-home portion of the exam may not be discussed with
your classmates.

# Group Project

During the semester, students are expected to work on a capstone project within 
a group. The capstone project is meant to either showcase a newly implemented 
statistical algorithms OR extend existing functions in pre-existing packages. 
Examples of past group projects have included: Data Cleaning Shiny Application, 
LinkedIn Connection Scrapper and Network Visualizer, and Visualization Support
for Probability Distributions. Students should choose a topic that interests
them but is reasonable to complete within the scope of the class. Due to the
amount of projects and the individual demands of each group's project, the
course staff will only provide *advice* -- not code -- during Office Hours.
Failure to have a working project by the time of the final presentation day 
will result in a severe penalty.

The groups will be created using the [CATME](http://info.catme.org/) system.
The use of this system is meant to create **strong** groups that are able to 
effectively work together. Specifically, students will be grouped together by
leadership styles, schedule availability and skill level. Each group will
have between 3 to 5 students.

There are four different phases of the group project: **Project Proposal Presentation**,
**Progress Report Presentation**, **Final Project Presentation**, and 
**Final Project Report**. Each of the phases is worth **10%**  making the 
overall project grade **40%** of the course total.  At the end, students will be
asked to perform peer evaluations of group members that may influence the grades
of students who do not contribute equally to the group project. As a results, 
students should view project grades as being tentative.

## Project Proposal Presentation

The project proposal presentation must be **5 - 7 minutes** in duration and
consist of no more than 12 slides (not including reference slides). 

Within the group project proposal, students should answer the following
questions:

1.	**Problem / Topic:** 
    * What problem or topic are you addressing? 
    * Why is it interesting or important?
    * What evidence supports this conclusion? 
2.	**Idea:** 
    * What is your idea for addressing the problem or topic? 
    * Why is it original relative to prior work? 
    * Where did the idea come from?
3.	**Relevance:**
    * How does your idea match with the course’s focus on statistical programming? 
4.	**Method:** 
    * What is your general plan for realizing the idea? 
5.	**Feasibility:** 
    * Is this project able to be completed before the end of the semester?
    * What steps must occur to complete the project before the end of the semester?
6.	**Time Schedule and Work Division:** 
    * What is the work plan to accomplish the necessary tasks before the end of the semester?
7.	**Preliminary Work:** 
    * What have you done or learned anything so far for the project? 
8.	**References:** 
    * Provide a list of papers or items you have read to write this proposal. 

## Progress Report Presentation

The project progress report presentation up should describe the present status 
of the project. The progress presentation must be **5 - 7 minutes** in duration
and consist of no more than 12 slides. Specifically, the slides should address
the following points:

1. How is the project progressing?
2. What has been accomplished thus far?
3. What have you learned? 
4. What issues have arisen?

Please **avoid** including code snippets. However, clear functional output is
okay.

The score for the progress report is based on how much work has been completed 
since the project proposal was initially submitted.

## Final Project Presentation

There will be 15 minutes during class that is allocated to the presentation of
your project.  Please focus on the outcomes of the project. The score is based
solely on how well the project outcomes and methods used are conveyed. There
should be no more than 12 slides (not including references) in the presentation.

## Final Report

Please prepare the final report using the following outline: 

1.	Introduction
2.	Related Work
3.	Method
4.	Results
5.	Discussion
6.	Conclusion
7.	References

Reports will be graded based upon project outcomes, the execution of methods 
described, and writing quality.

# Software

The course will use and present the **R** statistical computing language as well
as different parts of C++ through [Rcpp](http://gallery.rcpp.org/). The 
integrated developer environment that we will use to explore *R* is
[RStudio IDE](https://www.rstudio.com/products/rstudio/) made by
[RStudio Inc](https://www.rstudio.com). You are free to use any language you
choose, but the course staff will only be able to provide support for **R**. If
you would like to use another statistical computing environment, please alert
the instructor ASAP to discuss feasibility.

# Course Grades

| Type             | Percentage     | Total Points |
|------------------|----------------|--------------|
| Participation    | 15             | 15           |
| Midterm Exam     | 20             | 20           |
| Final Exam       | 25             | 25           |
| Group Project    | 4 x 10         | 40           |
| **Course Total** |                | **100**      |

# Grading Scale

| A+  | A   | A-  | B+  | B   | B-  | C+  | C   | C-  | D+  | D   | D-  |
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| TBD | 96% | 93% | 90% | 86% | 83% | 80% | 76% | 73% | 70% | 66% | 63% |

Grades are not curved or adjusted. This is not to dishearten students, but to 
let them know that their grade is based on individual effort and not on 
comparative effort.

# Academic Integrity

The official University of Illinois policy related to academic integrity can be 
found in Article 1, Part 4 of the Student Code. [Section 1-402 in particular 
outlines behavior which is considered an infraction of academic 
integrity.](http://studentcode.illinois.edu/article1_part4_1-402.html) 
These sections of the Student Code will be upheld in the STAT 385 classroom. 
Any violations will be dealt with in a swift, fair and strict manner. 

You may discuss methods for completing the exercise assignments with other 
students, but the execution of these methods and the preparation of the document
must be done independently. Sufficient evidence of sharing results, collaborating
on written assignments, or simply relying on internet resources will result in a
score of 0 for the assignment. There can be no discussion with other students or
collaboration of any kind on the take-home exams.

To ensure that you do not violate the academic integrity policies, all code and
solutions should be prepared yourself. All code should be typed yourself,
**not** copy and pasted. (Except for code provided in class or in the textbook.)


# Changes

The instructor reserves the right to make any changes he considers academically
advisable. Such changes, if any, will be announced in class. Please note that it
is your responsibility to attend the class and keep track of the proceedings.

Also, if changes are made... 

<iframe width="420" height="315" src="https://www.youtube.com/embed/WpE_xMRiCLE" frameborder="0"></iframe>
