## Homework Assignment 4 - Experiments

Version History: 

- Released 2020/4/8

This assignment is due **WEDNESDAY** May 6, 11:59 PM.

Create your homework repository in github classroom:
[https://classroom.github.com/a/Wn7OqS_7](https://classroom.github.com/a/Wn7OqS_7).
At the time of submission, it should contain one PDF file named
`HA4-FamilyNameGivenName.pdf.`You may include other files, e.g., a file
downloaded from Google Sheets, as supplementary material.

In your PDF, please complete the following problems below. Each problem will
specify what should be shown. If your solution requires multiple calculations
and you are using a spread sheet or other program to help, please clearly
label what is going on in each step in a way that can be seen without
interacting with the program. 

Example 1: If you use a spreadsheet, each sub-result should have a label
next to it explaining what the sub-result is and how it was calculated,
visible from the PDF, even if you include the spreadsheet file. I should not
have to open the spreadsheet file to see what it is. 

Example 2: If you use a script, each sub-result should have a comment above it
explaining what it is and what the code does to generate it.


### Section A: Experiment Design

For each of the scenarios A.1 and A.2, describe an experiment that tests the
idea in question. Describe:

- the independent variables and their conditions in the experiment and your
  justification/explanation for each (2 pts)
- dependent variables and your justification/explanation for each (2 pts)
- control variables, random variables, and confounding factors and your
  justification/explanation for each (4 pts)
- the population, how participants would be drawn from it, how many would
  participate, and how they would be assigned to trials (3 pts)
- the type of tasks the participants would perform, where the differences
  in trials would arise from (e.g., what changes in data?), and what order the
  trials would be given in (3 pts)
- your data analysis procedure including whether you would prune data points
  (and why) and what statistical tests you would use to analyze the collected
  data (and why) (3 pts)
- the limitations of your study, why may it not apply to someone else's
  similar problem? (2 pts)

If there are multiple possible criteria / interpretations to the scenario,
choose one that you think is among the most important, describe what it is,
explain why it is important, and design the rest of the experiment (e.g.,
tasks, variables) with that particular criteria / interpretation in mind.

In some cases, your answer may be dependent on information you do not know but
could discover in piloting. In those cases, note where you would pilot and
what you would determine from the pilot for your answer.

See lecture slides list statistical tests that can be used for greater than
two conditions.

#### A.1 Default brightness setting for a smart watch

What is a good default brightness setting on a smart watch?


#### A.2 New Items

Suppose you're a developer with an online commerce website. Presently the
website has a "New Items" category in its tab menu. You suggest adding a "New
Items" card to the images first shown under the menu which are currently top
recommendations. Which design is better for having visitors make any order
whatsoever?

#### A.3 Number of Participants (EXTRA CREDIT: 10 pts)

Suppose you are planning a within subjects experiment to determine if there's
a meaningful difference in smart phone typing speed between tapping the on
screen keys and gesture typing (draggging between keys). You plan to give
participants messages to type. From piloting, you estimate that tapping the
keys takes an average of 31 seconds for your trials with a standdard deviation
of 5 seconds. From this data you are also comfortabble with assuming the
distribution is normal. You consider a difference in order time of 20%
meaningful. How many participants do you need for your experiment assuming the
commonly accepted level of significance and power? How many participants would
you need if a difference of 10% was meaningful?

You may calculate this yourself or use a tool (including online). If you
calculate this by hand, include any reference material you used and describe
each step in the calculation. If you use a tool, explain why you chose the
tool, what settings you used, and why. Include screenshots. Also, include the
URL if the tool is online. In either case, if you had guidance (e.g.,
StackOverflow post), cite that guidance.


### Section B: "By-Hand" Statistical Analysis

For Problems B.1 through B.3:

1. State what statistical test should be used. (3 pts)
2. Calculate the test statistic. Show your work. (e.g., where applicable: sample means, sample
   standard deviation, evidence/argument of meeting test assumptions,
obbserved and expected outcomes, degrees off freedom, etc.) (10 pts)
3. State where there is a statistically significant difference. (2 pts)

You may use an existing tool to calculate the sample mean and sample standard
deviation (if required), as well as perform any basic arithmetic operation
(addition, subtraction, multiplication, division, square root, etc.) 

**You may not use a tool geared towards doing the entire statistical test for
you.** You may however verify your result using a program that performs the
test directly. If you choose to do this, you must still include the
sub-results as described above. Note that in class, we used the Student's t test
for both paired and independent unequal variance samples. The latter is often
replaced by the Welch's t test in practice, and thus stats programs may
perform the latter. You may choose to do the latter by hand when applicable
but if you do so, please make it clear.

The experiments and data described in this section are fictional and for
educational purposes only. 

#### B.1 Mobile Text Entry 

A manufacturer of third party gaming controls runs an experiment to compare
their new software-assisted button-press detection to the more traditional
standard button-press detection. In the experiment, 18 participants were asked
to play a simple test game. The controller switched between standard modde and
software-assisted mode between rounds of the game. The order of trials was
randomly set per participant. Through a series of tasks, a measure of the
participant's accuracy percentage in the game was recorded as follows: 


Standard: [33.8, 27.0, 28.7, 36.2, 32.3, 20.1, 29.8, 14.2, 24.5, 18.1, 25.7, 32.3, 26.8, 25.6, 22.2, 18.7, 32.5, 24.0] 

Software-Assisted: [32.5, 20.2, 19.6, 35.2, 36.9, 24.1, 48.2, 18.4, 30.4, 28.5, 40.3, 41.8, 31.2, 33.0, 22.9, 14.2, 27.2, 31.3]

Is there a significant difference in accuracy between the two? 

#### B.2 Product Search 

An online store runs an experiment to compare how quickly people can find a
specific product, given its attributes (e.g., color, size, brand), on their
website. With a group of 50 participants, 25 were randomly assigned an
interface where the search results would automatically update on changing any
attribute parameter and the other 25 were shown an interface where it would
only update when clicking a specifically marked search button. The measured
times (in seconds) were as follows:

Automatic Update: [48.3, 47.2, 39.5, 42.3, 35.6, 32.2, 29.6, 62.6, 40.4, 41.1, 33.7, 52.0, 30.5, 43.1, 36.9, 48.5, 40.4, 34.4, 44.7, 48.9, 45.6, 47.7, 39.3, 41.7, 38.9]

Search Button: [41.1, 33.7, 30.1, 35.7, 33.4, 28.5, 36.9, 31.4, 35.2, 37.9, 45.5, 39.6, 30.1, 36.6, 32.3, 31.5, 32.7, 33.8, 35.2, 40.3, 38.6, 36.9, 28.9, 41.0, 42.6]

Is there a significant difference in search speed?

### B.3 Email Redesign 

An online email service is re-designing its site. When a user logs in, they
will be offered a tour of the new design. The service wants to know which of
two welcome screens, one framed with palm trees and the other a simple
rectangle, results in more people starting the tour. The service randomly
selects 1,000 users and shows them the re-design early. Of the users, 500 get
the palm  trees and the rest the rectangle. In post-processing the data, a
few users were removed because they spent less than a second on the site. The
data kept indicated that 30 people started the tour of the 493 people who saw
the speech bubble and 45 people started the tour of the 491 people who saw the
rectangle.

Is there a significant difference in reaction to the two welcome screens?


### B.4 Bootstrap Confidennce Intervals: Navigation

Designers ask participants to rate how much they like each of three navigation
re-designs for their website: Double Tab, Fly Out, and Trail. The tasks were
completed by 17, 19, and 22 participants respectively. The following ratings
were recorded:

Double Tab: [7.6, 5.9, 7.3, 6.5, 7.3, 6.9, 7.5, 6.2, 6.3, 8.0, 8.4, 5.8, 8.7, 3.9, 6.0, 4.5, 7.9]

Fly Out: [10.0, 8.7, 8.3, 9.9, 10.0, 8.9, 7.7, 6.8, 8.6, 9.9, 8.7, 10.0, 10.0, 6.2, 8.2, 8.5, 9.6, 6.5, 7.4]

Trail: [7.6, 10.0, 7.8, 5.0, 6.3, 8.3, 10.0, 7.7, 7.9, 10.0, 10.0, 7.7, 8.2, 8.5, 6.2, 8.8, 9.7, 2.5, 7.7, 9.5, 9.1, 8.3] 


a) Calculate 95% bootstrap confidence intervals as described in class. Use
1,000 resamples. You may use Javascript or Python, but you may not use a
library that calculates them for you. Include your code in a separate file.
This code does not have to follow any specific architecture like MVC. (9 pts)

**Tip:** If you use Python, use a `seed` function (e.g., `numpy.random.seed`)
to set a seed value for the random number generator. This allows you to get
reproducible results even with random calls, making things easier to debug.
Unfortunately, no such functionality exists for Javascript's `Math.ranndom()` 

b) What are the confidence intervals of the conditions (in interval format)? (3 pts)

c) Plot the confidence intervals. (3 pts)

d) What can be inferred from these intervals? (2 pts)
