---
layout: page
title: Syllabus
description: >-
    Course syllabus and information.
nav_order: 2
---

# Syllabus
{:.no_toc}
This page contains the most updated syllabus for the course.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is this course?

This is a topics course meant to strengthen the mathematical fundamentals for students wishing to pursue further study in machine learning. The serious study of machine learning requires a student to be proficient in several prerequisite subjects: (i) linear algebra, (ii) multivariable calculus, and (iii) probability and statistics. This course assumes that the student has already taken courses in these subjects at the undergraduate level (it is not a replacement), but would like to be more comfortable with their mathematical maturity in any of these areas before approaching a formal course in machine learning at the level of, say, COMS 4771.

We will not give comprehensive treatment of each of these areas; instead, we will present the main results that are most relevant to the analysis and design of machine learning models. Alongside the theory, we will also motivate each topic with numerous applications and examples relevant to machine learning so they are more familiar when encountered in future study.

Topics will include (but are not limited to): span, linear independence, bases, orthogonality, singular value decomposition, eigenvalues and eigenvectors (linear algebra), vector calculus, continuous optimization, convex optimization (calculus and optimization), review of basic probability, exponential families, and multivariate Gaussians (probability and statistics). Machine learning applications will include initial exposures to: principal component analysis, facial recognition, and gradient descent.

### Structure of the course
This is a course with a loose story. The course is structured around two main ideas that underlie modern machine learning: least squares regression and gradient descent. Very informally, least squares regression is a classic way of modeling problems in machine learning (the “what”), and gradient descent is the workhorse algorithm that drives much of modern machine learning (the “how”). Every week, we’ll develop and motivate these two ideas in lecture with the tools and concepts you learn from each part of the course. As the class goes on, you’ll develop different perspectives on these two ideas from, first, what we learn in linear algebra, then calculus and optimization, and, finally, probability and statistics. The hope is that, by the end of the course, you’ll have a deep understanding of both these ideas in ML while also having two concrete “applications” to motivate all the abstract mathematical tools and concepts you learn in the course.

**If you'd like to see the original rationale for creating this course: [Rationale]({{ site.baseurl }}/assets/files/rationale.pdf).**

## Who, What, When, Where?

- **Instructor:** Samuel Deng ([samdeng@cs.columbia.edu](mailto:samdeng@cs.columbia.edu)).
- **Teaching Assistant:** Christopher Lee ([csl2183@columbia.edu](mailto:csl2183@columbia.edu)).
- **Dates and times:** Mondays and Wednesdays 10:10am - 1:20pm ET.
- **Location:** 833 Mudd. My office hours will be in the DSI Suite in Conference Room 417 (enter Mudd at the 4F campus level, make a left in the opposite direction of the CS department towards Chef Mike's Pizza Pi).
- **Office Hours:** See the [Calendar]({{ site.baseurl }}{% link calendar.md %}) and watch for announcements on Ed for any changes.
  - Sam: Mondays 3pm - 5pm ET; Wednesdays 3pm - 5pm ET, both in DSI 417 in Mudd. Zoom will be available on Wednesday office hours. 
    - Please come to my (Sam's) office hours once, if only to introduce yourself! If you can't make my office hours, please email me to setup another time to meet.
  - Chris: *TBD.*

## Prerequisites

This course is not meant to be a replacement for the undergraduate level courses that are already prerequisites to machine learning:
- Multivariable calculus at an undergraduate level (e.g., Math 1201, Math 1205).
- Linear algebra at an undergraduate level (e.g., Math 2010, COMS 3251).
- Probability theory (with calculus) at an undergraduate level (e.g., Math 2015, Math 1201). 
- Discrete mathematics at an undergraduate level (e.g., COMS 3203).

Instead, this course assumes familiarity with the above prerequisites and our main goal will be to focus on building up to advanced topics, techniques, and applications from the above subjects that may have been glossed over in an introductory course that will be useful in further study of machine learning. That being said, we *do not* assume that you are an expert in any of the above prerequisites to take this course; we hope that the additional practice you receive in this course gets you a little closer to that.

This course will also integrate some basic numerical Python programming to allow students to get comfortable with numerical computing packages such as `numpy` and `pandas` before using them more intensively in a future machine learning course. Because of this, we *recommend* previous exposure to basic Python programming, but this is not strictly required if you are willing to learn the basics as the course progresses. Previous exposure to programming (possibly in a different language) should be sufficient for this. The required programming for this course will be relatively light.

If you are unsure if you meet the prerequisites above, please email the instructor.

## Resources and Links

There will be no official textbook for this course, but we will (very) roughly follow some of the topics and applications from the textbook *Mathematics for Machine Learning* by Marc Peter Deisenroth, A. Aldo Faisal, and Chen Soon Ong. All slides will be published before each lecture in [Course Content]({{ site.baseurl }}{% link content.md %}) so students can follow along during lecture. Optional readings will occasionally be posted.

Though this class assumes that you’ve taken courses in each of the following areas, you may want to brush up. Along with *Mathematics for Machine Learning* by Marc Peter Deisenroth, A. Aldo Faisal, and Chen Soon Ong, here are a few more undergraduate-level resources for the following subjects.

### Linear Algebra
- *Linear Algebra and Applications* by Gilbert Strang
- [Gilbert Strang's MIT Course on Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- *Linear Algebra Done Wrong* by Sergei Treil, available free as [PDF here](https://www.math.brown.edu/streil/papers/LADW/LADW.html)
- [Daniel Hsu's course notes for Computational Linear Algebra](https://www.cs.columbia.edu/~djhsu/CLA/)
- [3Blue1Brown's Essence of Linear Algebra videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

### Multivariable Calculus
- [MIT OpenCourseware course on multivariable calculus](https://ocw.mit.edu/courses/18-02sc-multivariable-calculus-fall-2010/)
- *Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach* by Barbara Burke Hubbard and John H. Hubbard.
- *Vector Calculus* by Susan Jane Colley

### Probability Theory and Statistics
- [*Introduction to Probability for Data Science*](https://probability4datascience.com/) by Stanley H. Chan
- *A First Course in Probability*  by Sheldon Ross.
- *Introduction to Probability* by Joseph K. Blitzstein and Jessica Hwang.
- *Probability and Statistics for Engineers and Scientists* by Ronald E. Wadpole.

Additional resources can be found in the Resources section of the [Course Content]({{ site.baseurl }}{% link content.md %})
page, to be updated as the class progresses.

## Assignments and Grading Policy
This course will be evaluated on the basis of five weekly problem sets and a final project. There are no exams.

### Problem Sets

To give you practice and reinforce the concepts learned in class, there will be five weekly problem sets. The problem sets will usually have about four to five theoretical problems with an additional coding exercise to reinforce the concepts and develop basic fluency in machine learning packages such as `numpy`, `pandas`, and `sklearn`. The problems will be proof-based, but we will aim to develop your mathematical maturity in reading and writing proofs throughout the course.

Each problem set will be released on Mondays and will cover the material taught in lecture on Monday and Wednesday that week. They will be **due the following Thursday at 11:59pm ET.** All problem sets should be submitted to [Gradescope](https://www.gradescope.com/courses/801399) as a PDF file, generated from LaTeX using the provided template files. Solutions will be released on Mondays. Detailed homework submission instructions can be found in [HW Submission]({{ site.baseurl }}{% link homework.md %})

This course is intended to prepare students for further courses in machine learning, which all require  typesetting (at least at Columbia). LaTeX is also a useful skill to have for future courses or research, and LaTeX documents just look clean. **Because of this, we will require that your assignments be typed in LaTeX to give you practice**; the problem sets in COMS 4771 are hard enough without needing to wrestle LaTeX typesetting issues! Resources and a submission template will be provided to learn LaTeX and gently onboard students. 

[Overleaf](https://www.overleaf.com) is the standard online platform for typesetting LaTeX, a bit like Google Docs. You are welcome to generate your LaTeX submissions however you'd like; we only need your PDF. [Here's a quick resource to get you up to speed for typesetting in LaTeX](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes).

*Because of the accelerated summer schedule, less focus will be put on the coding aspect of the course as to not overwhelm students, particularly in the pilot version.*

### Late Policy
Every student has a total of 4 late days for the course. Late time is rounded *up* to the nearest day and is measured from submission time on Gradescope. **No homework will be accepted after 11:59 PM ET on the Sunday after the initial due date** (3 late days' time). This rule is here to allow us to post solutions to each of the problem sets in a timely manner. No further late days will be given for the course, so please plan accordingly.

 If you need an **emergency** exception to the late work policy, please email me before the due date with your reason(s) and a new proposed due date. I'm happy to discuss accommodations. 

### Regrade Policy
If you believe that a problem of yours has been graded incorrectly, submit a regrade request on Gradescope with a clear argument detailing why you believe
the grade is incorrect **within 7 days after the assignment is graded.** We will respond to your regrade request within a week. All regrades are final.

### Grading Scheme
Your final grade in the course will be determined by the following formula:

*16% * (5 homeworks) + 20% * final project = 100%*,

with the following grade cutoffs:
- A: 93.0% and above
- A-: 90.0 - 92.9%
- B+: 87.0 - 89.9%
- B: 83.0 - 86.9%
- B-: 80.0 - 82.9%
- C+: 77.0 - 79.9%
- C: 73.0 - 76.9%
- C-: 70.0 - 72.9%
- D: 60.0 - 69.9%

### Final Project
The final project of this course will be to *attempt* to read a research paper in machine learning. Emphasis on *attempt*: there is no expectation that you will understand every single detail in the paper. However, you might be pleasantly surprised that you understand a bit more than you would’ve at the beginning of the course just by strengthening your mathematical foundations.

There are three parts to this project:

1. **Choose a paper.** *Within the first week.* We will provide a list of machine learning papers from recent conferences in machine learning that represent some topics from the cutting edge of current research. Your job is to just peruse the list, browse the abstracts, and choose a paper that seems interesting to you based on its title and abstract alone.
2. **Beginning of course evaluation.** *Before the second week.* You will attempt to read the whole paper. Research papers can be intimidating if you’ve never read one before (and even if you’ve read hundreds!) so we will provide some guidance on how to read a scientific paper in machine learning. Then, you will provide a critical evaluation of the paper to the best of your current ability based on a template we will supply. This will be graded on completion and effort.
3. **End of course evaluation.** *Final week.* At the end of the course, you will read the paper again. You will fill out a similar critical evaluation of the paper, per the same template.


This project will be graded on the clarity and quality of the evaluation, but we stress that we will not focus on how much you “get” the paper. The emphasis of this project is on your own growth — hopefully, you’ll find that by the end of the course your chosen paper isn’t quite as perplexing as it may have seemed in the beginning.

## Course Outline (Summer Schedule)
The course will be split into three main parts, for each “pillar” of mathematics that underlies machine learning. Throughout the course, we will aim to alternate between theory and application. In particular, the course will focus on developing two concepts that are central to machine learning: *least squares regression* and *gradient descent*. By the end of the course, the hope is that you have a varied and nuanced understanding of each of these concepts as well as scaffolding to "hang your hat on" for each of the disparate mathematical ideas we've learned/reviewed throughout the course. Other applications relevant to machine learning will also be introduced throughout.

Although each third of the course will focus on a certain mathematical theme, they will not be disjoint – each week will build on the one before, so we strongly encourage attending and carefully reviewing each lecture as the semester proceeds.

This is a course outline for a six week summer version. Because of the accelerated schedule, less focus will be put on the coding aspect of the course as to not overwhelm students, particularly in the pilot version.

*This is a preliminary outline of the class topics! For an updated outline and corresponding lecture materials, see [Course Content]({{ site.baseurl }}{% link content.md %}).*

### Linear Algebra
  - Week 1-1: Introduce the basic machine learning problem: least squares regression. Review of basic linear algebra (vectors, matrices, linear independence, span, and bases).
  - Week 1-2: Subspaces, orthogonality, norms, projections. Relationship of least squares to projection.
  - Week 2-1: Singular value decomposition, matrix approximation, pseudoinverse. Perspective on least squares with SVD.
  - Week 2-2: Eigenvalues, eigenvectors, positive definite/semidefinite matrices, and the spectral theorem. Principal components analysis and facial recognition.
### Calculus and Optimization
  - Week 3-1: Vector calculus (derivatives, gradients, matrix calculus). Least squares as an optimization problem. Introduce the machine learning workhorse: gradient descent.
  - Week 3-2: Linearization and Taylor series. Proof for the convergence of gradient descent.
  - Week 4-1: Basics of continuous optimization: constrained optimization and Lagrange multipliers. Least squares with regularization.
  - Week 4-2: Convex optimization. Solving least squares using gradient descent.
### Probability and Statistics
  - Week 5-1: Probability fundamentals (random variables, expected value, variance, law of large numbers, central limit theorem). Stochastic gradient descent.
  - Week 5-2: Statistics fundamentals (basic distributions, bias, variance, sufficient statistics). Least squares and the Gauss-Markov Theorem.
  - Week 6-1: Statistics fundamentals continued (conjugacy, exponential family). Gaussian and multivariate Gaussian distribution. Model of Gaussian errors, maximum likelihood estimation and least squares.
  - Week 6-2: Multivariate Gaussian. Gaussian mixture models and density estimation. Review of course.

## Collaboration Policy
Learning is best done in collaboration with peers. To this end, you will be allowed to collaborate with other students on the problem sets in groups **up to three students (including yourself)**. All collaborators must write the names and UNIs of their group at the top of each problem set (the template will have a space for you to do so). All collaborators must also *type up everything in their own words*. You are free to discuss, whiteboard, and brainstorm with your collaborators. However, when it comes to sitting down and solving the actual problem, you must do it yourself, away from your collaborators.

For the final project, only individual work is allowed. The final project is meant to track your own individual growth in mathematical maturity (which may have improved from collaborating with other students!), so you should aim to do all parts of it yourself.

## Course Philosophy and Feedback
The goal of this course is to reinforce and deepen important mathematical fundamentals, gain better intuition of these mathematical tools, and develop confidence in mathematical maturity. All of these require work that may sometimes seem daunting, but I believe that any student is capable of growing in the course, so long as they continually grapple with the concepts and do the work. This may, at times, be difficult, but struggle is a totally normal part of the process. I was in your shoes, at one point (and still am!), and I can assure you that many of these concepts seem really difficult until they inevitably, after plugging away for a while, become natural. I hope you, the student, come away with this feeling as well.

By the nature of this course, students will come from widely different levels of background, and it is my job to make sure that no student is left behind or glossed over because of this. To this end, if there’s anything I can do to help you learn better, do not hesitate to contact me directly or leave anonymous feedback.

This is also a new course, so any feedback would be much appreciated to iterate and improve it! If you have any feedback at all about the course or my teaching of the course, please submit through this [anonymous feedback form](https://forms.gle/fYbJrUCgPyvJeM93A).