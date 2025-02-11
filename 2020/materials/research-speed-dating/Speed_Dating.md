<style>

.reveal section p {
  color: black;
  font-size: .7em;
  font-weight: normal;
  font-family: 'Helvetica'; #this is the font/color of text in slides
}


.section .reveal .state-background {
    background: white;}
.section .reveal h1,
.section .reveal p {
    color: black;
    position: relative;
    font-family: 'Helvetica';
    font-weight: normal;
    top: 4%;}
   
 
 /* section titles */
.reveal h1 { 
  color: black;
  position: relative;
  font-weight: normal;
  font-family: 'Helvetica'; 
  top: 4%
}    

 
/* slide titles */
.reveal h3 { 
  color: black;
  font-weight: normal;
  font-family: 'Helvetica'; 
}    

.small-code pre code {
  font-size: 1.2em;
}

</style>



Research Speed Dating
========================================================
author: Chris Bail, 
date: SICSS
autosize: true
transition: none

========================================================

# **STRENGTHS OF GROUP PROJECTS**


1. Better Science
========================================================

1. Better Science
========================================================

<img src="Uzzi et al.png" height="400" />

1. Better Science
========================================================

<img src="impact.png" height="400" />


2. This may be especially true for CSS
========================================================


2. This may be especially true for CSS
========================================================

<img src="colore_by_nodes_arial.png"/>

3. Group Projects may be the Most Efficient Way for us to Learn from Each Other
========================================================




========================================================

# **CHALLENGES OF GROUP PROJECTS**


Challenges
========================================================
&nbsp; 

1. Tremendous diversity of skills  
2. Ensuring good group chemistry 
3. Limited time 
4. Different goals?
5. Free-riding


SICSS Group Projects
========================================================
&nbsp; 

1. Can take on many forms (from original empirical reseaarch to creation of open-source tools)
2. In one week, many groups will only find enough time to create a proposal, though some may have pilot results by the end of the week.
3. Limited seed funding may be available at your site for pilot research and/or data purchasing, cloud computing costs.
4. Additional funding may be available at your site after the end of the week.

========================================================

# **RESEARCH SPEED DATING**


Research Speed-dating
========================================================
&nbsp;  

1. We crowdsource a list of research interests in a google doc (5 min)
2. Each person writes a "1" next to their research interests (5 min)
3. We identify maximally similar clusters of participants
4. We identify maximally different clusters of participants

Research Speed-dating
========================================================
&nbsp;  

1. Maximally similar clusters come up with a group project (30 min)  
2. Maximally different clusters come up with a group project (30 min)  
3. We start a new google doc. Each person takes 5 minutes to write down their favorite group project idea  
4. Everyone puts their name next to the group project they want to join  


Research Speed-dating
========================================================
&nbsp;  

1. Have lunch today with your group in order to begin discussing your project.  
2. It is ok to change groups until the end of today.



Timeline for this week
========================================================
&nbsp;

Monday: develop group project ideas and make research teams

Tuesday morning: write brief (<1 page) proposal 

Tuesday afternoon: the organizer of your site will begin responding to seed funding requests on a rolling basis (if funds are available)

Tuesday afternoon-Thursday night: work on group projects  

Friday (all day): group presentations (with feedback)


Deliverable
========================================================
&nbsp;

A document that contains a presentation of your group project that is between 10-20 minutes that explains:  

1) Why your group project is important 

2) What are your hypotheses?  

3) What will you collect? 

4) What are the next steps? 

Note: not all projects will work; if yours fails, please write a post-mortem that explains why.


========================================================

# **LET'S BEGIN**



Let's crowdsource a list of our research interests
========================================================
&nbsp;

Place the name of a research interest in the first column of this
document, and write a "1" across all research interests you have:

https://tinyurl.com/y867xb4s



Read the Googlesheet
========================================================
class: small-code 
&nbsp;










```
processing file: Speed_Dating.Rpres

Attaching package: 'janitor'

The following objects are masked from 'package:stats':

    chisq.test, fisher.test

Reading from "SICSS Research Speed-Dating"
Range "'Sample'"
Quitting from lines 201-216 (Speed_Dating.Rpres) 
Error: Assigned data `values` must be compatible with existing data.
ℹ Error occurred for column `email`.
x Can't convert <double> to <character>.
Backtrace:
     █
  1. ├─knitr::knit(...)
  2. │ └─knitr:::process_file(text, output)
  3. │   ├─base::withCallingHandlers(...)
  4. │   ├─knitr:::process_group(group)
  5. │   └─knitr:::process_group.block(group)
  6. │     └─knitr:::call_block(x)
  7. │       └─knitr:::block_exec(params)
  8. │         ├─knitr:::in_dir(...)
  9. │         └─knitr:::evaluate(...)
 10. │           └─evaluate::evaluate(...)
 11. │             └─evaluate:::evaluate_call(...)
 12. │               ├─evaluate:::timing_fn(...)
 13. │               ├─base:::handle(...)
 14. │               ├─base::withCallingHandlers(...)
 15. │               ├─base::withVisible(eval(expr, envir, enclos))
 16. │               └─base::eval(expr, envir, enclos)
 17. │                 
Execution halted
```
