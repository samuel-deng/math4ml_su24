---
layout: page
title: Course Content
description: Listing of course modules and topics.
---

# Course Content
{:.no_toc}
This page includes all the content for the course thus far. We will update this page with all lecture materials, readings, and homework
as the class goes on.

1. TOC
{:toc}

## Schedule and Main Content

This class has six main modules, two for each "pillar" of machine learning: linear algebra, calculus  and optimization,
and probability and statistics. All class files will be available here. For a more detailed outline of the course thus 
far, see the [Course Skeleton]({{ site.baseurl }}{% link skeleton.md %}).

- Lecture slides can be found by clicking on the lecture title for the appropriate day.
- All readings on the right column are **optional**, but reading (a subset of) these materials before each lecture might help digesting the content during lecture.
- Problem sets will be posted here, as well as their solutions.

This is a tentative schedule and is subject to change. Readings, slides, and assignments will be posted as the class goes on. 

In the readings, *MML* refers to [*Mathematics for Machine Learning*](https://mml-book.github.io/) by Marc Peter Deisenroth, A. Aldo Faisal, and Cheng 
Soon Ong. *VMLS* refers to [*Introduction to Applied Linear Algebra - Vectors, Matrices, and Least Squares*](https://web.stanford.edu/~boyd/vmls/) by Stephen Boyd
and Lieven Vandenberghe. 

{% for module in site.modules %}
{{ module }}
{% endfor %}

## Resources
I'll update this with additional resources as the class progresses. Feel free to use these or ignore completely. If you
know of any additional resources that you think would be helpful for the class, let me know and I'll add it here!

### LaTeX
- [Overleaf](https://www.overleaf.com), the Google Docs for LaTeX. Can be used for all the assignments in this class.
- Overleaf's guide to [learn LaTeX in 30 minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes#Display_math_mode)
- David Xiao's [Beginner's guide to LaTeX](https://www.cs.princeton.edu/courses/archive/spr10/cos433/Latex/latex-guide.pdf)
- Eddie Kohler's [LaTeX usage notes](https://www.read.seas.harvard.edu/~kohler/latex.html). These might be worth a browse to rectify common stylistic problems with using LaTeX.
- [Detexify](https://detexify.kirelabs.org/classify.html), an applet to get the LaTeX command for any handwritten symbol.

In general, Googling an issue you're having with LaTeX usually provides a plethora of solutions.

### Linear Algebra Prerequisites
If you need to refresh any linear algebra, these may be good resources.

- *Linear Algebra and Applications* by Gilbert Strang
- [Gilbert Strang's MIT Course on Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- *Linear Algebra Done Wrong* by Sergei Treil, available free as [PDF here](https://www.math.brown.edu/streil/papers/LADW/LADW.html)
- [Daniel Hsu's course notes for Computational Linear Algebra](https://www.cs.columbia.edu/~djhsu/CLA/)
- [3Blue1Brown's Essence of Linear Algebra videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

### Multivariable Calculus Prerequisites
If you need to refresh any multivariable calculus, these may be good resources.

- [MIT OpenCourseware course on multivariable calculus](https://ocw.mit.edu/courses/18-02sc-multivariable-calculus-fall-2010/)
- *Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach* by Barbara Burke Hubbard and John H. Hubbard.
- *Vector Calculus* by Susan Jane Colley

### Probability Theory and Statistics Prerequisites
If you need to refresh any probability and statistics, these may be good resources.

- [*Introduction to Probability for Data Science*](https://probability4datascience.com/) by Stanley H. Chan
- *A First Course in Probability*  by Sheldon Ross.
- *Introduction to Probability* by Joseph K. Blitzstein and Jessica Hwang.
- *Probability and Statistics for Engineers and Scientists* by Ronald E. Wadpole.