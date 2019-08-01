# Project Proposal

## High Level Summary

My program, the Master’s in Educational Technologies and Applied Learning Sciences (or METALS for short) prides itself on being one of the few places at CMU dedicated to the study of education.  Common sense dictates that education professors are generally better at teaching than those who have not dedicated their life to learning this field.  However, METALS professors are also not education professors, but rather those who have simply made education their area of study.  It will be interesting to see if METALS professors also can fit the bill of being generally better at teaching than their general HCI colleagues.  

## Story Structure

Setup: Metals currently advertises 100% career placement and what do people do

Conflict: This tells very little about what the program experience itself is like

Resolution: METALS should also advertise the excellence in teaching their professors give

User Stories: 

1. As a reader I want to come to METALS, so that I can learn from all these great teachers

2. As a reader I want to know what classes are the highest/lowest rated, so I can take/avoid those classes

## Initial sketches

![Sketches](/IMG_20190724_051810[1].jpg)

## The data

The data comes from the faculty evaluation database that stores all the faculty evaluations from across CMU’s many different schools since 2008.  It can be found at this website: https://wwwh3.smartevals.com/reporting/StudentsSeeResults.aspx.  The specific data I’m using is a cleaned up, filtered version of this very large dataset that includes only courses from the HCI department and only courses 2015 onwards due to a different system of tracking how many hours were spent on the course before 2015.  As METALS’ first year was in 2013, the loss of data is minimal due to the previous problem.  The specific variables I’ll potentially use from the evaluation are year the course was taught, course ID, professor teaching the course, response rate, number of hours per week needed for class, and overall teaching rating.  Variables thrown out include section number and all the specific rating questions.  These are all too detailed and will likely have little information gain for the reader compared to the trouble it will be to comprehend the extra information.

## Method and medium

The story will be delivered via an infographic made through shorthand.

# User Testing

## Wireframes/Storyboard

https://docs.google.com/presentation/d/1K6Q3CyhVtBq8R_MmciU2vj5AvImrBMMVGPiO35s-1sw/edit#slide=id.g5e593d8e32_0_133

## Testing Protocol

### a. The target audience: 

The incoming METALS Cohort

### b. Approach in identifying representative individuals to interview: 

Ideally, this would be the target audience, as some are already on campus.  However, none could be found in the time given.  Three adjacent individuals were chosen instead.  Two are current METALS students and another a friend who is about to go back to school and is in process of choosing classes.

### c. Interview script:

So today, I'm going to show you a presentation that includes several data visualizations, all of them rough drafts, and I'd like you to give me some feedback on them.  This is meant to a presentation with the incoming METALS cohort in mind, but just talk about the presentation and data visualizations from your point of view.

(After each visualization) What did you notice? What was your take away from this visualization?
(After Visualization 1) I wanted to showcase that most core classes are pretty good, particularly EGIA, while Tools was not so good.  Did you get this message at all?  What detracted from this message, what could help enhance this message?

(After visualization 2) I wanted to showcase which electives are highly rated, and which ones are less so. Did you get this message at all?  What detracted from this message, what could help enhance this message?

(After visualization 3) I wanted to showcase that Capstone is all over the place, and also massive amounts of work. Did you get this message at all?  What detracted from this message, what could help enhance this message?

(After the whole presentation)What are you thinking about after seeing the presentation?  What more did you want to know from the graphs?  The presentation as a whole?

### The findings from the interviews

##### "Jesus, this is a crime scene" -Interviewee 3

Overall every visualization had too much information and poorly organized

A unanimous opinion was that the constant overlap of circles and text made interpretations extremely cognatively demanding


##### "Ah, I didn't get that until you explained it to me" - Interviewee 1

Several points were too subtle or hidden for users to pick up.

The size of the circles to denote the amount of hours that a class requires was impossible to compare for the first visualization

The current grading scale of 1 to 5 has no reference

##### "This would be really useful as I sign up for classes" - Interviewee 2

Some concepts shown through 

All three users could tell that Tools for Online Learning was particularly bad and Educational Goal, Instruction and Assessment was very good.

Two liked the idea of being able to see clusters of where a particular class' data laid in visualization 2, to see consistency, as well as if it was regularly near the top.

Capstone has a massive courseload, but that wouldn't have been my main focus if it weren't for the title - Interviewee 1

All three users noted the positive correlation between giving feedback and having clear learning goals.  That said, this is all likely to be from good teaching in general, and it is not the right  message to be giving to the audience.

Two users thought the entire presentation was quite interesting

##### "..." -All three interviewees

None of the users could state any call to action from the presentation

#### Planned changes to address feedback

Averaging all the year's courses into just one point to decrease dots

Color coding each course

adding on a best for 5 and worst for 1 would help give the graphs some reference

Use different shapes to compare METALS classes vs. HCI ones to help have some further distinguishment from all the overlapping circles.

Use color gradient for work involved instead of size of circles

Rethink story for better call to action
