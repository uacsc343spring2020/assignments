## Project Milestone 7

Version History: 

- Clarification 2020/4/18 - Video hosting
- Released 2020/4/16

The team portion of this milestone is due Friday May 1, 11:59 PM.

The individual portion for this milestone are due Saturday May 2, 0:29 AM.

In this milestone we are:

- Iterating on the design based on the suggestions from PM6,
- Iterating on the functional prototype for our interface in Javascript/HTML/CSS,
- Demonstrating the functional prototype,
- Documenting the prototype, 
- Reflecting on the interface design/project, and
- Individually stating your contributions and the contributions of your team
  members to this milestone.

Create a team repository:
[https://classroom.github.com/g/MxLKCsw7](https://classroom.github.com/g/MxLKCsw7) 
At the time of submission should contain your write up. Continue updating your
prototype in your previous Demo directory.

Your write up should be `PM7.html` plus any CSS files, Javascript files,
images or media needed.  No style information should be in the HTML tags. Do
not use HTML tags like `<center>`, `<b>`, or `<i>` to alter visual appearance. 

Use the following link to create your individual github repository for this
assignment:
[https://classroom.github.com/a/sgXSfu1t](https://classroom.github.com/a/sgXSfu1t)
At the time of submission, it should contain a text file named
`PM7-evaluations.txt` **and the other `PM7-reflection.txt`.** 
The first file should have the content described under
Individual Evaluations below. This is a similar format used in PM6. The second
file is specified in this document.

Also, the notes on how you may want to distribute the work are different. 


### Prototype (35 pts)

The Demo repository from PM6 should contain the working prototype of your design.
We should be able to recreate your demonstrations in the accompanying movie.
Name the first page we should load `index.html.` We may also test out other
scenarios as a future evaluation participant might.

Recall that the focus of this project is on designing the *interface* and thus
you will be graded on code supporting the interface/prototype and not backend
business logic. Before adding a feature, consider whether it is in support of
the interface functionality (clearly some non-visible state must be kept for
example) or is application logic not necessary for the prototype to function.

For teams that had payment systems in their prototype, continue to include
only up to the interface to select payment type. For instance, some of you had
card swipers in your paper prototype. This is less feasible in the functional
prototype. 

We expect you to continue to use some form of modularization/structure in
developing this prototype. You do not have to follow the strict MVC used in
homework assignments and exams, but there should be some separation of the
data state from the interface. The interface should not be monolithic.
Document this choice in the Write Up.

The prototype will be assessed in the following manner:

Suitability as a Design Artifact (20 pts)

* Can this prototype be effectively used to evaluate the design?
  * To what extent does it match the design? (may be mitigated by explanation in write up)
    * Are the UI elements from the design there?
    * Does the behavior match what is described in the design or shown in
      previous prototypes?
  * Is the functionality in a state where the interactions can be evaluated?
    * Is a user/study participant likely to run into bugs?

Maintainability (15 pts)

* Use of modularization and structure
* Documentation including that in the write up


### Write Up `PM7.html`

The write up should be in the same format as the previous several milestones.
At the top of the report, state the names of all the team members as well as
your team name.

#### Revised Design (15 pts)

Create a section called "Revised Design."

**Create screen shots of your functional prototype from PM5 and clearly mark
where the design changes are to take place and what they will be. These should
reflect what you believe needs to be changed for the iteration, *not* what you
end up coding. Design first, then implement.**

Beneath the revised design, explain what changes were made *to the design*
(not the functional prototype). Order this list by priority of the change
(most important chages first).

For each change, indicate:

1. What was the impetus for the change (e.g., PM6 observations, feedback grom
   classmates, seeing other classmates' work, etc)

2. Whether you are aiming for this task to be done this milestone. 

The goal of this section is to continue to design as if this project were to
continue. You will not be expected to implement them all in this milestone.
Choose a subset that is reasonable. It may be one major change or a number of
small ones. **You will not be graded on whether this matches what is
implemented.  This is an exercise in priorities and planning.**

It may be the case that a great suggestion only comes from the project
presentations a few days before the deadline. You will not be expected to
implement this change, but acknowledge its priority for the next cycle. 

#### Prototype Demonstration (10 pts)

**We may run out of large file space on Github. In that case, it's okay to
host the video on YouTube or link it to Google Drive or elsewhere. Just be
sure the video is accessible from email.arizona.edu and cs.arizona.edu
accounts.**

Under the header "Prototype Demonstration", embed a movie showing the
prototype through three different scenarios. For example, one can show the
scenario of a user who is familiar with the interface and knows exactly what
she wants while another could show a user who has to do more searching. **Show
all of the functionality/design of the prototype through these three
scenarios.**

Describe the scenarios either verbally through the movie as some of you did
before or in text below it. Similarly, describe what the user is doing either
verbally during the movie or in text below it.

**You may use the same scenarios from PM5 ONLY IF combined they exercise all
the features of your prototype.**

#### Documentation: Architecture 

Create a section called "Documentation: Architecture." In it, explain the
software architecture/decomposition of your prototype. How are the interface
elements divided in the code? What other structures exist (e.g., to hold state
or logic)?

**Tie the names of your important functions or other structures in the code to
your explanation of the Architecture. Consider a new programmer to the project
who wants to see a particular structure, what would they search for in the
code?**

**Explain any changes made from your architecture in PM5.**

You may refer to the names put forth in this section for your individual
evaluations when explaining everyone's contributions.

#### Documentation: Third Party Elements Used

Create a section called "Documentation: Third Party Elements Used." List any
Javascript libraries or other third party files used in your prototype and a
link to their source. Briefly state how they are used in your prototype.
**Include any you already documented in PM5.**

#### Documentation: Differences from Design

Create a section called "Documentation: Differences from Design." Describe any
components of the interface that are not in the prototype for any reason
(e.g., ran out of time, technological considerations) and any components that
were added for any reason (e.g., started too small so adding from extended
tasks). Include the reason for the change.

We will use this to inform the evaluation of the prototype's readiness to
evaluate the interface design. We recommend building up from the most
important parts of the interface first: those absolutely necessary to complete
the primary user tasks **and/or those that were considered the most essential
changes based on feedback from your observations and from your class
presentation.**

#### Project Conclusion and Reflection (15 pts)

Create a section called "Project Conclusion and Reflection." Describe:

1. What changes should be made to the design that have not yet been made.
   Order these by magnitude of the change.

2. What features are necessary to add to the current prototype to test it for
   production readiness.

3. What were the key points learned through the design process. In particular,
   what design decisions were made that should be avoided and what were made
that were particularly helpful. These can be at any scale from the choice of
font to the overall structure. If someone were to start a similar interface
project, what could they learn from your experience here? (These will likely
be a superset of issues raised  during your project presentation.)


### Format (4 pts, incl. names) 

The only constraints on the format, other than those described above, are as
in PM5 onward:

- The report should be reasonably readable. For example, black text on a black
  background is not reasonable. 
- The headers should be differentiable from the body text and spacing should
  be used to help readability.
- There should be some persistent way for me to navigate between sections.
- The title should have your group name.  
- The report content should be 640 pixels wide with a 12 point sans-serif
  font for the report text.


### Individual Reflection (16 pts)

This content should be written by each individual near the project's
completion. Please name the file `PM7-reflection.txt` and put it in your
individual repository.

In the file, answer the following questions. All quesitons refer to the
project in its entirety. You can answer in terms of the design, utility of
specific milestone assignments, group work, technical issues, and/or anything
else related to this project.

1. If you had to do the project over again, what would you have done
   differently and why?

2. If you had to do the project over again, what would you keep the same and
   why?

3. What are your key take-aways from this project? What did you learn from the
   experience? 

4. Was there anything that surprised you, if so, what? If not, what was your
   expectation and how was it met?

This section will be graded on completeness (are the questions answered?) and
thoroughness in explaining your findings (why did you come to the conclusions
you did? what particular parts of the project led you to those conclusions?)


### Individual Evaluations (5 pts)

This content should be written by each individual after the project milestone is
submitted. Use the separate individual github classroom link.

At the top of your evaluation, estimate the distribution of work contributed
by yourself and your teammates. You will do this by starting with 20 units for
each members of your team (a total of 60 for a 3 person team, 80 for a 4
person team). You will then apportion the units to yourself and your team
members to indicate distribution. If everyone has 20 unit, that means equal
distribution.

We will assess the distributions listed as well as the contributions described
for balance and may apply a weighting/scaling factor to individual grades to
account for discrepancies. More work does not necessarily mean a higher
grade--taking over the project and influencing others to not participate is
discouraged.


Example:
```
Unit Distribution

Blinky: 17

Pinky: 21

Inky: 22

Clyde: 20

```

**If the distribution is largely uneven, please make a note as to why it
was not evenly apportioned and what was done to try to divide it evently.**

The second paragraph should describe what your contributions to the project
milestone were:

```
Individual Contributions -- FamilyName, GivenName

My contributions were...
```

Then, for each of your team members, write a section headed with their name
explaining what their contributions were and rating them on:

1. Quality of Work
2. Timeliness of Work Completion
3. Contributions to Group Discussion
4. Cooperative and Supportive Attitude

Ratings should be one of [Below Expectations, Good, Above and Beyond]. 

Beneath the ratings you may provide more detail explaining your ratings or any
other information we should know.


Example:
```
Peer Assessment -- FamilyName, GivenName

GivenName's contributions were... 

1. Quality of Work: Good

2. Timeliness of Work Completion: Below Expectations

3. Contributions to Group Discussion: Good

4. Cooperative and Supportive Attitude: Good

GivenName did a good job on the paper prototype but was two days later than we
planned so we had to scramble to make the movie.

```

### Distribution <strike>(5 pts)</strike>

**Distribution grading suspended for COVID-19**

All team members should participate in the discussion of what changes to make
to the interface design.

The team should strive to apportion equitably. It is up to the team how this
can be done. 

Each team member must contribute to the programming of the prototype in some
way. Consider the natural decompositions (e.g., different panels like menu,
order summary, customization as well as the overall navigation and internal
state, logic and interface) in your prototype as well as how you decomposed
the problem before.

Additionally, testing, documentation, styling, and asset development (i.e.,
finding images) and acquistion are important and time-consuming components.

As with the previous milestones, it may also help to appoint different people
to draft each writing section and then someone else to check/edit the writing
for completeness. Similarly, one person can be in charge of assembling the
webpage and another in charge of checking it for compliance. 



