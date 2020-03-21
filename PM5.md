## Project Milestone 5

Version History: 

- Released 2019/3/20

The team portion of this milestone is due Friday April 3, 11:59 PM.

The peer evaluations for this milestone are due Saturday April 4, 0:29 AM.

In this milestone we are:

- Sketching a revised design based on the suggestions from PM4,
- Creating a functional prototype for our interface in Javascript/HTML/CSS,
- Demonstrating the functional prototype,
- Documenting the prototype, and
- Individually stating your contributions and the contributions of your team
  members to this milestone.


Create a team repository:
[https://classroom.github.com/g/iiSacEXt](https://classroom.github.com/g/iiSacEXt) 
At the time of submission should contain your prototype in a directory called
`prototype` and file named `PM5.html.` It
should also include any CSS files, Javascript files, images or media needed
for the report and `PM5.html`. The `prototype` directory should include all
files necessary for your prototype. Please name the file to launch your
prototype, `start.html`. 

Use the following link to create your individual github repository for this
assignment:
[https://classroom.github.com/a/BXOngp6P](https://classroom.github.com/a/BXOngp6P)
At the time of submission, it should contain a text file named
`PM5-evaluations.txt.` The file should have the content described under
Individual Evaluations below. This is a similar format used in PM3 with one
change. See bolded comments below.  Also, the notes on how you may want to
distribute the work are different. 

Underneath the PM5 folder, create a folder called `prototype`. It should
contain all files necessary for your prototype.

The *report* (`PM5.html`) should be presented in a single HTML page as
described below. No style information should be in the HTML tags. Do not use
HTML tags like `<center>`, `<b>`, or `<i>` to alter visual appearance. 

The *prototype* may use third-party Javascript libraries and CSS files as long
as it is not a library that has specific functionality for creating these
kinds of ordering kiosks/game inventory systems/interfaces. Your prototype
should include these libraries and codes locally rather than linking to the
web. That way, we can be sure we are using the same version. Any third-party
code you use should be documented in the report.


### Prototype (65 pts)

The `prototype` directory should contain the working prototype of your design.
We should be able to recreate your demonstrations in the accompanying movie.
Name the first page we should load `index.html.` We may also test out other
scenarios as a future evaluation participant might.

Recall that the focus of this project is on designing the ~interface~ and thus
you will be graded on code supporting the interface/prototype and not backend
business logic. Before adding a feature, consider whether it is in support of
the interface functionality (clearly some non-visible state must be kept for
example) or is application logic not necessary for the prototype to function.

For teams that had payment systems in their prototype, include only up to the
interface to select payment type. For instance, some include card swipers in
their paper prototype. This is less feasible in the functional prototype. 

We expect some form of modularization/structure to be used in developing this
prototype. You do not have to follow the strict MVC used in homework
assignments and exams, but there should be some separation of the data state
from the interface. The interface should not be monolithic. Document this
choice in the report.

The prototype will be assessed in the following manner:

Suitability as a Design Artifact (40 pts)

* Can this prototype be effectively used to evaluate the design?
  * To what extent does it match the design? (may be mitigated by explanation in write up)
    * Are the UI elements from the design there?
    * Does the behavior match what is described in the design or shown in
      previous prototypes?
  * Is the functionality in a state where the interactions can be evaluated?
    * Is a user/study participant likely to run into bugs?

Maintainability (25 pts)

* Use of modularization and structure
* Documentation including that in the write up

Note PM7 will be the second round of prototyping at this level and will
incoropriate what was learned in the evaluation (by observation) of PM6.
Likely you will use this prototype as a base for the next one, so please
implement with this in mind. 


### Write Up `PM5.html`

The write up can be in the same format as the previous two milestones, as long
as it is readable. The constraints are unchanged. At the top of the report,
state the names of all the team members as well as your team name.

#### Revised Design (10 pts)

Create a section called "Revised Design."

Create a sketch (or electronic mockup) of the revised design. Indicate all
dialogs and interactions.  Include an image of it in this section.

**This sketch should be done BEFORE you begin coding your prototype. Please do
not create the prototype and then create the sketch after the fact to match.
It is OKAY if the prototype does not fulfill everything in the sketch.
Remember this is as much about the PROCESS as it is about the product.**

Beneath the revised design, explain what changes were made. Indicate which
came from your observations and which came from other sources.

#### Prototype Demonstration (10 pts)

Under the header "Prototype Demonstration", embed a movie showing the
prototype through three "ordering lunch" (MENU) or "finding an inventory item"
(GAME) scenarios where in each one the demonstration is different. For
example, one can show the scenario of a user who is familiar with the
interface and knows exactly what she wants while another could show a user who
has to do more searching.

Describe the scenarios either verbally through the movie as some of you did
before or in text below it. Similarly, describe what the user is doing either
verbally during the movie or in text below it.

If we did not make any suggestions about your scenarios in the previous
milestones, you may use them again or you may change them to match the
prototype you built. 

#### Documentation: Architecture 

Create a section called "Documentation: Architecture." In it, explain the
software architecture/decomposition of your prototype (e.g., MVC, MVC as
implemented by [framework of choice], MVVM, Flux, Redux, something homegrown
(please describe)... don't worry if you don't know what some of those are).
How are the interface elements divided in the code? What other structures
exist (e.g., to hold state or logic)?

You may refer to the names put forth in this section for your individual
evaluations when explaining everyone's contributions.

#### Documentation: Third Party Elements Used

Create a section called "Documentation: Third Party Elements Used." List any
Javascript libraries or other third party files used in your prototype and a
link to their source. This includes images you did not create yourself.
Briefly state how they are used in your prototype. If you didn't use any, just
write "None."

#### Documentation: Differences from Design

Create a section called "Documentation: Differences from Design." Describe any
components of the interface that are not in the prototype for any reason
(e.g., ran out of time, technological considerations, etc) and any components
that were added for any reason (e.g., started too small so adding from
extended tasks). Include the reason for the change.

We will also use this to inform the evaluation of the prototype's readiness to
evaluate the interface design. we recommend building up from the most
important parts of the interface first: those absolutely necessary to complete
a basic order.

Remember that this project is about the *process* of interface design as much
as the product. It is *okay* to not achieve all goals. There is value in
being aware of potential further features. They can be prioritized in a future
iteration.


### Format (5 pts, incl. names) 

The only constraints on the format, other than those described above, are as
in PMs 3 and 4:

- The report should be reasonably readable. For example, black text on a black
  background is not reasonable. 
- The headers should be differentiable from the body text and spacing should
  be used to help readability.
- There should be some persistent way for me to navigate between sections.
- The title should have your group name.  
- The report content should be 640 pixels wide with a 12 point sans-serif
  font for the report text.

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
was not evenly apportioned and what was done to try to divide it evenly.**

**Note, it may be that some team members are unable to participate due to
COVID-19 related changes (e.g., Internet access, illnness, need to care for
family). This will not be counted against any team. Please prioritize health
and family.**

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

### Distribution (5 pts)

All team members should participate in the discussion of what changes to make
to the interface design.

The team should strive to apportion equitably. It is up to the team how this
can be done. 

Each team member <s>must</s> (should, leeway given due to COVID-19) contribute
to the programming of the prototype in some way. Consider the natural
decompositions (e.g., different panels like menu, order summary, customization
as well as the overall navigation and internal state, logic and interface) in
your prototype. 

Additionally, testing, documentation, styling, and asset development (i.e.,
finding images) and acquistion are important and time-consuming components.

As with the previous milestones, it may also help to appoint different people
to draft each writing section and then someone else to check/edit the writing
for completeness. Similarly, one person can be in charge of assembling the
webpage and another in charge of checking it for compliance. 

