# Project Proposal

## High Level Summary

My program, the Master’s in Educational Technologies and Applied Learning Sciences (or METALS for short) prides itself on being one of the few places at CMU dedicated to the study of education.  Common sense dictates that education professors are generally better at teaching than those who have not dedicated their life to learning this field.  However, METALS professors are also not education professors, but rather those who have simply made education their area of study.  It will be interesting to see if METALS professors also can fit the bill of being generally better at teaching than their general HCI colleagues.  

#### Edit July 31st: 

Upon playing around with the data, my initial story is unable to be supported as data points showed all METALS courses falling within the full range of HCI courses.  I have thus changed the story to be more of an overview of METALS courses and how it may help guide new METALS students to better select their courses.

## Story Structure

Setup: METALS currently advertises 100% career placement and what do people do

Conflict: This tells very little about what the program experience itself is like

Resolution: METALS should also advertise the excellence in teaching their professors give

User Stories: 

1. As a reader I want to come to METALS, so that I can learn from all these great teachers

2. As a reader I want to know what classes are the highest/lowest rated, so I can take/avoid those classes

#### Edit August 7th:

Setup: METALS is an interdisciplinary program where you are expected to learn principles of learning science/education, technology/programming, and design thinking/skills

Conflict: No one comes in with expertise in all three categories and classes can take longer or shorter depending on what you have expertise in

Resolution: Care should be taken in deciding what electives to choose so that you will not be overwhelmed in any one semester

User Stories: 

1. As a reader I want to know what classes might be harder for me

2. As a reader I want to know what classes I should choose every semester so I won't be overwhelmed


## Initial sketches

![Sketches](/IMG_20190724_051810[1].jpg)

## The data

The data comes from the faculty evaluation database that stores all the faculty evaluations from across CMU’s many different schools since 2008.  It can be found at this [website](https://wwwh3.smartevals.com/reporting/StudentsSeeResults.aspx).  The specific data I’m using is a cleaned up, filtered version of this very large dataset that includes only courses from the HCI department and only courses 2015 onwards due to a different system of tracking how many hours were spent on the course before 2015.  As METALS’ first year was in 2013, the loss of data is minimal due to the previous problem.  The specific variables I’ll potentially use from the evaluation are year the course was taught, course ID, professor teaching the course, response rate, number of hours per week needed for class, and overall  rating.  Variables thrown out include section number and all the specific rating questions.  These are all too detailed and will likely have little information gain for the reader compared to the trouble it will be to comprehend the extra information.

## Method and medium

The story will be delivered via an infographic made through infogram.

# User Testing

## Wireframes/Storyboard

[click here to be taken to google slides storyboard](https://docs.google.com/presentation/d/1K6Q3CyhVtBq8R_MmciU2vj5AvImrBMMVGPiO35s-1sw/edit#slide=id.g5e593d8e32_0_133)

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

##### _"Jesus, this is a crime scene" -Interviewee 3_

Overall every visualization had too much information and poorly organized

A unanimous opinion was that the constant overlap of circles and text made interpretations extremely cognatively demanding


##### _"Ah, I didn't get that until you explained it to me" - Interviewee 1_

Several points were too subtle or hidden for users to pick up.

The size of the circles to denote the amount of hours that a class requires was impossible to compare for the first visualization

The current grading scale of 1 to 5 has no reference

##### _"This would be really useful as I sign up for classes" - Interviewee 2_

Some concepts shown through 

All three users could tell that Tools for Online Learning was particularly bad and Educational Goal, Instruction and Assessment was very good.

Two liked the idea of being able to see clusters of where a particular class' data laid in visualization 2, to see consistency, as well as if it was regularly near the top.

Capstone has a massive courseload, but that wouldn't have been my main focus if it weren't for the title - Interviewee 1

All three users noted the positive correlation between giving feedback and having clear learning goals.  That said, this is all likely to be from good teaching in general, and it is not the right  message to be giving to the audience.

Two users thought the entire presentation was quite interesting

##### _"..." -All three interviewees_

None of the users could state any call to action from the presentation

#### Planned changes to address feedback

Averaging all the year's courses into just one point to decrease dots

Color coding each course

adding on a best for 5 and worst for 1 would help give the graphs some reference

Use different shapes to compare METALS classes vs. HCI ones to help have some further distinguishment from all the overlapping circles.

Use color gradient for work involved instead of size of circles

Rethink story for better call to action

# Final Story

<div class="infogram-embed" data-id="_/JLhS7w9iXRgQRIN1rITk" data-type="interactive" data-title="What Electives Should a METALS Student Choose"></div><script>!function(e,t,s,i){var n="InfogramEmbeds",o=e.getElementsByTagName("script")[0],d=/^http:/.test(e.location)?"http:":"https:";if(/^\/{2}/.test(i)&&(i=d+i),window[n]&&window[n].initialized)window[n].process&&window[n].process();else if(!e.getElementById(s)){var r=e.createElement("script");r.async=1,r.id=s,r.src=i,o.parentNode.insertBefore(r,o)}}(document,0,"infogram-async","https://e.infogram.com/js/dist/embed-loader-min.js");</script>

Visit the [original](https://infogram.com/1p1jmpqln35gejfmd2wr0wz6jqb6g5pq53e?live)

### Additional Notes

The only two audiences who would usually care about teacher evaluations are the teachers themselves and future students.  With the data no longer supporting the original claim that METALS professors are better than their peers, the audience turned to future students.  Some of the planned changes I thought up of from user testing were general ways to make the data more readable and understandable, such as averaging the data to have less points and using some color codes.  But specifically for the audience, I also made the change to show METALS classes only, as METALS students would not care about classes they couldn't take.  In addition, I removed the variable of course ratings and thus a full axis from required courses, as even a horribly rated course like Tools for Online Learning has to be taken anyway.

All these changes I feel greatly focuses the story, both in terms of choosing exactly what content is most useful to my audience and giving nothing more as well as using visualizations in a way that keeps them from becoming too busy.  Basic graphs are all that's needed to get my point across.  I admit I did not put too much thought into the colors of the infographic.  I simply chose the METALS colors of red, black and white.  I did however, put some thought into how to actually present all these graphs.  I worked basically in the order I would tell my story: 

First level : Everyone is specialized in something when they come in, and this tends to be evenly distributed among the three subjects METALS students are required to learn

Second level: That specialization informs how much time you'll spend on your core classes, which, perhaps interestingly to the outsider, seems to be longer if you are an expert in that particular class.  Some further digging outside of this data would have alumni telling you that this makes sense because the program requires everyone to work together to cover each others' weaknesses and you'll often be consulted as the expert for the classes that come easy to you, driving up your workload.

Also second level: The enigma that is capstone, which comes in the Spring, always takes a lot more than the advertised 12 credits, and seemingly on the rise as the years progress.

Third level: Since METALS students are required to take two specializations for their electives, so no staying only an expert in what you came in with, it's important to consider exactly what electives to take based on course rating and how much work the course gives.

The first level gives background, the second level gives information on the inevitable, and after containing those pieces of information, the student is ready to see the third level, which gives information that the student actually has power over.  This is also the thinking process that METALS students should have as they think about electives.



(Data used can be found in the small type at the bottom of the infographic)
