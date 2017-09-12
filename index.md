title: Computer Graphics Course
author: Alec Jacobson
html header:  <link rel="stylesheet" href=style.css>

# Computer Graphics CSC418 _Fall 2017_

![](images/fields-cafe.jpg)

- [Sections](#sections)
- [News](#news)
- [Links](#links)
- [Lecture Schedule](#lectureschedule)
- [Assignments](#assignments)
- [Recommended Textbook and References](#recommendedtextbookandreferences)
- [Grading](#grading)

## Sections

**LEC0101** Wednesdays 12:00-14:00 in GB 220  
Prof. [Karan Singh](http://www.dgp.toronto.edu/~karan/)  
karan@dgp.toronto.edu  
+1 416-978-7201  
Office hours Wednesdays 14:00-16:00 in BA 5258

**LEC0201** Tuesdays 15:00-17:00 in GB 220  
Prof. [Alec Jacobson](http://www.cs.toronto.edu/~jacobson/)  
jacobson@cs.toronto.edu  
+1 416-946-8630  
Office hours Tuesdays 17:00-19:00 in BA 5266

**Tutorial** for both sections will be held _together_ on Mondays 12:00-13:00 in GB
220.

## News

| Date Posted | Anouncement |
|-------------|-------------|
| 11/9/2017   | Welcome to CSC418 |

## Links

- [Bulletin Board](https://bb-2017-09.teach.cs.toronto.edu/c/csc418)
- _Course Information Sheet (coming soon...)_

## Course Overview

This course introduces the basic concepts and algorithms of computer graphics.
It covers the basic methods needed to model and render 3D objects, including
much of the following: graphics displays, basic optics, line drawing, affine and
perspective transformations, windows and viewports, clipping, visibility,
illumination and reflectance models, radiometry, energy transfer models,
parametric representations, curves and surfaces, texture mapping, graphics
hardware, ray tracing, graphics toolkits, animation systems.

**Prerequisites:** CSC336H1/CSC350H1/CSC351H1/CSC363H1/364H1/CSC365H1/CSC373H1/CSC375H1/378HI, MAT137Y1, CSC209H1/proficiency in C or C++ ; CGPA 3.0/enrolment in a CSC subject POSt.

The student is expected to read background material on the hardware and local
software, and should be comfortable with elementary linear algebra, geometry,
and vector calculus. It is also assumed that the student is comfortable
programming in basic C++.

**Recommended preparation:** MAT237Y1, MAT244H1.

## Lecture Schedule

Links to lecture slides are _**required readings**_. These links are available
before each lecture (but may be minimally altered for the lecture).

Online notes present the slides in greater detail and are strongly suggested
reading.  Sections under the Textbook column refer to strongly suggested
readings from Shirley's textbook.  External links point to online resources
(e.g., Wikipedia and MathWorld) that you may find helpful. _They are not required
readings._

<!-- Pressing OPT+[Space] will produce a non-breaking space. For example,
between "Tutorial" and "1" so these appear on the same line -->

|            | Topics              | Slides | [Shirley](#textbook) Chapters |
|:----------:|:--------------------|:-|:-|
| **Part I: Basic Graphics Primitives** ||||
| Tutorial 1 | _Hello, I'm your TA. There's no tutorial this week._ |  |  |
| Lecture 1  | **Introduction & raster operations** Line drawing, 2D [polygons](http://mathworld.wolfram.com/Polygon.html), parametric 2D curves (circle, [ellipse](http://mathworld.wolfram.com/Ellipse.html))  <br> [Introduction.pdf](notes/Introduction.pdf) <br> [Curves.pdf](notes/Curves.pdf) <br> Wikipedia [List of curves](https://en.wikipedia.org/wiki/List_of_curves) | [lecture1.pdf](slides/lecture1.pdf), [lecture1_6up.pdf](slides/lecture1_6up.pdf) | 3.1-3.5; 2.5-2.6 | 
| Tutorial 2 | C++, OpenGL and Hierarchical Models | | |
| Lecture 2  | **Interpolation & 2D Transformations** Rigid, conformal, affine transformations. Homogeneous coordinates. Coordinate-free geometry. <br> [Transforms.pdf](notes/Transforms.pdf) <br> [Coordfreegeom.pdf](notes/Coordfreegeom.pdf) | [lecture2+3.pdf](slides/lecture2+3.pdf), [lecture2+3_6up.pdf](slides/lecture2+3_6up.pdf) | 6.1; 2.4; 6.3 | 
| Tutorial 3 | C++, OpenGL and Hierarchical Models | | |
| Lecture 3  | **3D Surfaces** Planes, tangents, normals, bilinear patches, quadrics/superquadrics. 3D transformations. <br> [3dobjects.pdf](notes/3dobects.pdf) | | 2.9–2.11; 13.1; 6.2 | 
| **Part II: Viewing in 3D** ||||
| _coming soon_ ||||
| **Part III: Appearance Modeling and Rendering** ||||
| _coming soon_ ||||
| **Part IV: Interpolation and Animation** ||||
| _coming soon_ ||||

## Assignments 

[Academic Honesty (Please Read!!!)](#academichonesty)

Links to assignments will be available on the hand-out dates

_Tentative dates based on 2016. Proper 2017 dates coming soon..._

| Date handed out | Due date | Assignment | Helper code
|:----------------|:---------|:-----------|:---:|
| Sept. 20 | Oct 11 | | |
| Oct 11   | Nov 1 | | |
| Sept. 13 | Wooden Monkey: Dec. 3 <br> Dec. 6 | | |


## Recommended Textbook and References

Currently, there is no textbook that reflects all the material covered in this
class. Only the **Slides** in the [Lecture Schedule](#lectureschedule) are
**required reading**.

In-class lectures will be supplemented by online notes (lecture slides
and course notes) as well as portions of the following recommended textbook:

### Textbook

- [_Fundamentals of Computer Graphics_](http://www.cs.utah.edu/~shirley/books/fcg2/), 2nd Edition, A.K. Peters by Peter Shirley.
Be sure to check the online errata and slides available on the above link.

Textbook sections and online notes listed next to each lecture are strongly suggested reading.

- _OpenGL Programming Guide: The official guide to learning OpenGL, version
  1.4_, By the OpenGL Architecture Review Board, Addison-Wesley.  This book will
  be a useful reference for getting some of the programming assignments done.
  (Also available online)
- _OpenGL Reference Manual_, By the OpenGL Architecture Review Board,
  Addison-Wesley. (Also available online) Supplementary Textbooks

We will not be using the following books directly, but they offer different
perspectives on the topics that will be covered in class.

- A. Glassner,                  _Principles of Digital Image Synthesis_, vol. 1&2, Morgan Kaufman, 1995
- J. Foley et al.,              _Computer Graphics: Principles and Practice_, Addison Wesley, 1997
- A. Watt,                      _3D Computer Graphics_, 3rd edition, Addison-Wesley, 1999
- D. Hearn and M. P. Baker,     _Computer Graphics_, 3rd edition, Addison-Wesley, 2003
- J. Blinn,                     _Jim Blinn's Corner: A Trip Down the Graphics Pipeline_, Morgan Kaufman, 1996
- J. Blinn,                     _Jim Blinn's Corner: Dirty Pixels_, Morgan Kaufman, 1998
- R. Fosner,                    _OpenGL Programming for Windows95 and NT_, Addison Wesley, 1998
- D. S. Ebert et al.,           _Texturing and Modeling_, 2nd edition, Academic Press, 1998
- G. Wolberg,                   _Digital Image Warping_, IEEE Computer Society Press, 1990

## Grading

|----:|---------------|
| 15% | In-class test
| 35% | Final exam
| 50% | Assignments

There will be three assignments in total, composing 10%, 15% and 25% of the
total grade, respectively. Assignments will be roughly tri-weekly. The
assignments will have a written portion and a programming portion.

### Late Policy

Assignments are **_due by 11:59pm_** on the due date. Assignments (including the
written part) should be submitted to the TA in electronic form. Exact submission
instructions will be provided with the first assignment. The written portions if
hand-written should be legibly scanned and submitted electronically as well.

For each day late, including weekends, 15% of the total possible points will be
deducted (a day ends at the due time).  

**No work will be accepted if it is more than five days late.**

### Academic Honesty

Academic honesty is a very serious matter and can result in very serious
consequences. Note that academic offences may be discovered and handled
retroactively, even after the semester in which the course was taken for credit.
This is a challenging class aimed at teaching you the fundamentals of computer
graphics. You wont learn much if you cheat but you might get a good grade if you
get away with it. If all you want is a good grade take an easier class where you
wont have to cheat!

For purposes of this class, academic dishonesty is defined as:

- Any attempt to pass off work on a test that didn't come straight out of your
  own head.
- Any collaboration on written or programming assignments (its ok to share ideas
  on programming assignments but the code MUST be your own) in which the
  collaborating parties don't clearly and prominently explain exactly who did
  what, at turn-in time.
- Any activity that has the effect of significantly impairing the ability of
  another student to learn. Examples here might include destroying the work of
  others, interfering with their access to resources (e.g., digital cameras), or
  deliberately providing them with misleading information.

### Email & Bulletin Board Traffic

- Please do not send email directly to the TAs. They will not be replied.
- Main forum for answering questions about class or about the assignments is the
  class bulletin board. The TAs will be monitoring the board.
- Appropriate use of the board: clarifications on assignment, on lecture
  material, general concerns about the course, or other remarks that are
  appropriate for all students to see/participate in.
- Do NOT broadcast pieces of your code or answers to written assignments to the
  bulletin board. Specific or general implementation questions whose answer
  would benefit all students in the class are appropriate. However: the bulletin
  board is NO replacement for the tutorial hour. That should be the main forum
  for asking/answering questions of this sort.
- Questions of the form "I cannot find the problem with my code; here it is, can
  you help me" are unlikely to be replied, so don't count on it. If you have a
  question with code, take it to the TA office hours or to the tutorials.
