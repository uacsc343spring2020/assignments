## Homework Assignment 3

Version History: 

- 2020/02/13: Fixed release year from 2019 to 2020, made note about `position: fixed;`
- 2020/02/11: Released

In this assignment, we are exercising:

- Improving an interface to adhere to design principles
- Writing our design rationale
- Getting more practice GUI programming in HTML/CSS/Javascript
- Getting more practice with the MVC design pattern

For this assignment, we iterate on the UI from HA2 using suggestions from
class in accordance with design principles. You may start from your HA2
submission or you may start from a sample solution available under the
resources tab of Piazza.

The HTML, Javascript, and CSS should be in separate files. No style information should be in the HTML tags outside of a `style` attribute. Do not use HTML tags like `<center>`, `<b>`, or `<i>` to alter visual appearance.  Avoid the use of CSS `position: fixed;` because it may cause elements to overlap and be unreadable on the grader's setup.

This assignment is not meant to require external Javascript libraries.
However, if you use external Javascript libraries, it should be included in
the repository. Do not use a library that already implements a TODO list.
That is not the goal of this assignment. Do not forget to cite any borrowed
code in your `HA3.js` document near where the borrowed code is used (other
than the files from Piazza). The grader should not be expected to install
anything. 

Use the following link to create your github repository for this assignment:
[https://classroom.github.com/a/_B61a3xk](https://classroom.github.com/a/_B61a3xk)
Your submission git repository should contain one HTML file named `HA3.html`
as well as a CSS file `HA3.css`, a JS file `HA3.js`, any additional files
needed for your design (e.g., images, libraries) and a plain text file
`README.txt`.

The title of the webpage should be "Last Name, First Name - HA3" where your
last name and first name are used.

The `README.txt` file should contain the rationale for your design decisions
as well as any elaboration on specific design principles as noted below.

This file also includes a rough breakdown of points, though points may also be
missed for not following instructions (e.g., adherence to HTML/CSS divide,
missing name, files not at root level of directory, etc.)

**Please note: I may share screen shots or movies of your HA3 and explain how
you chose to design the solution with the class. The focus would be on
positive elements of the design, not on functionality. Please let me know if
you are uncomfortable with your assignment being shown or if you wish for it
to be anonymized (shown without attribution to your name).**

### MVC (20 pts)

Like HA2, your javascript should demonstrate the Model-View-Controller pattern
as we went over in lecture. (If you are using external libraries, they must
work in concert with this pattern.)

The application and state data should be kept by the Model which notifies any
Views upon change.

Any changes to the DOM should be managed by the Views. 

The Controller should act as the mediator, making changes to the model as
notified by the Views. The Controller does not modify any Views.


### Functionality & Design (45 pts)

Most of the functionality from the previous homework assignment should be
preserved: Users should be able to add individual TODO items which have one of
the following categories: Work, School, and Play. Users should be able to
clear all items or mark individual items as finished.

#### New Functionality/Changes

In HA2, a finished item was removed from the view. In this assignment, you can
choose how to handle a finished item but you must explain your choice in the
rationale.

Empty items should not be added to the list. Instead, the error should be
handled. The design of this handling is your choice but must be justified in
the rationale.

There should be some sort of `Permit Easy Reveral of Actions` functionality
(e.g., undo). How exactly this is implemented is again your choice and must be
justified in the rationale. Hint for programming an Undo feature: Consider
using a stack.

Users should be able to edit items in the TODO list. How exactly this is
implemented is once again your choice and must be justified in the rationale.


#### Improving Design

In addition to the functionality changes above, we discussed in class several
reasons why we want to improve the interface for choosing a category (Work,
School, Play) (e.g., "Set Item Type"). Be sure to make changes to this portion
of the interface and argue for your changes in the design rationale.

Additionally, you may make any other changes to the interface design as long
as functionality is preserved. Your design, where you make changes or not,
should be justied in the design rationale.


### Design Rationale (30 pts)

Design and implement a new interface for this input. In your `README.txt`,
include a *design rationale* where you explain why you chose the design you
did. Your rationale should appeal to the design principles you're fulfilling
and explain any reasons/trade-offs for the design principles you are
violating. A good rationale will also discuss alternative designs and explain
why you chose your design over the alternatives.

Your new design may use elements of the old design, but they should be
justified.

Each element of the design rationale is graded on thoroughness, with maximum
points for a rationale that explains both functionality and presentation nand
uses multiple forms of evidence.
