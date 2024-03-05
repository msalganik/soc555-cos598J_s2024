---
title: Assignments
layout: home
menuItem: Assignments
menuPosition: 3
---

## Assignment 1: Evaluation and extension of Hegre et al.'s predictions of armed conflict
***

### Description

[Hegre et al. (2013)](https://www.jstor.org/stable/24016137) predict “changes in global and regional incidences of armed conflict for the 2010-2050 period.” [Hegre et al. (2021)](https://academic.oup.com/isq/article/65/3/660/6124679) evaluate these predictions over the 2010-2018 period. Both papers provide their code in their supplemental materials, and the UCDP/PRIO Armed Conflict Data Set is publicly available:
* [Hegre et al. (2013) replication materials](https://havardhegre.net/replication-data/)
* [Hegre et al. (2021) supplementary materials](https://academic.oup.com/isq/article/65/3/660/6124679?login=false#supplementary-data)
  * Tip: the authors include a readme file on running their code to reproduce visualizations from their article. If you want to reproduce those visualizations, you may need to make some tweaks to the dependency files, run.sh, and/or some of the R files to get the code to run. 
* [UCDP/PRIO Armed Conflict Data Set](https://ucdp.uu.se/downloads/)

You have two goals for this assignment:

1. **Evaluation.** Perform your own evaluation of the quality and value of the 2013 paper’s predictions over the 2010-2018 period. You have complete freedom on how you evaluate these predictions, as long as your decisions are justified. You may use the 2021 paper for inspiration, but your goal is not to simply replicate their evaluation procedure or results.

2. **Extension.** Extend the 2013 and/or the 2021 paper(s) in some way. Here are some possible directions, but please do not feel limited by these ideas:
* *Calibration.* How calibrated are the 2013 paper’s risk scores? Table 1 suggests that reducing the classification threshold can substantially increase the true positive rate without a large increase in the false positive rate.
* *Longer-run predictions.* How well do longer-run predictions from the 2013 paper’s models hold up? You could consider generating additional predictions from the 1970-2000 model and/or using additional data from the 2022 update of the UCDP/PRIO Armed Conflict Data Set.
  * *Time-varying drivers.* Relatedly, the 2021 paper states that “the results indicate that the drivers of armed conflict are fairly stable over time” because the model did not perform much worse over the 2010-2018 period than during the 2001-2009 period of the original study. But note that the latter and former are both the first 9 years after the cutoff dates for their respective models, and perhaps drivers do not shift in such a short term. Is there another way to get at this question of time variance of drivers?
* *Extending the original models.* Does training the original model on more available data help increase the effectiveness of these models? The 2021 paper suggests that adding data about political institutions could increase the predictivity of their models, and cites several recent papers with more comprehensive democracy data or forecasts of changes to political institutions.

### Groups

You should work on this assignment in groups of 2 - 3. Interdisciplinary groups are strongly recommended, but not required. If you would like to work in a group of 1 or 4, please email us for permission (we will only permit this if there is a compelling reason).

### Schedule

* **Wednesday, February 21, 2024, 11:59pm**: Send an email to Shreyas at sgandlur@princeton.edu with a sketch of how you intend to evaluate and extend the Hegre papers.
  * Please send one email per group and include the names of all team members.
  * You don’t have to stick to this sketch, but we do think it is important for you to spend some time thinking and designing your study before you begin computing.
  * If we think this sketch doesn’t meet the bar for what we’re looking for, we will let you know before class on Monday, February 26. If you don’t hear from us by then, you can assume that your sketch is adequate.
* **Wednesday, March 6, 2024, 11:59pm**: Send an email to Shreyas at sgandlur@princeton.edu with your completed assignment:
  * Along with a writeup, your submission should include documented code, any necessary datasets (or scripts to download such datasets), and a script that allows us to reproduce all the figures and numbers in your writeup. This is called computational reproducibility and is an important part of reproducible science.
  * Your submission can be a ZIP file or a link to a git repository (make a separate submission branch or tag if you plan to keep working on it).

We recognize that you only have 3 weeks to complete this assignment so please be realistic about what is possible. If the assignment seems interesting and generative, you are welcome to keep working on it for the final project.

This assignment is worth 25% of your course grade. We will evaluate you on problem selection, creativity, correctness, thoroughness, quality of writing, and related work. See [here](https://msalganik.github.io/soc555-cos598J_s2024/final_project.html#grading-rubric) for details. 


**Please submit on time. This being a grad seminar, adjudicating lateness penalties and such is not a good use of instructor time. If you are unable to submit on time due to unforeseeable circumstances, reach out to us.**


## Assignment 2: Participate in the Predicting Fertility data challenge
***

Participate in the <a href="https://stulp.gmw.rug.nl/prefer/">Predicting Fertility data challenge (PreFer).</a>

- Complete your application by Sunday, March 24, 2024.
- Submit a model by the last day of classes: Friday, April 26, 2024.
- Participants in the PreFer challenge will have the chance to be co-authors in a community paper and submit to a special issue of a journal, as described <a href="https://stulp.gmw.rug.nl/prefer/details/overview/6special_issue.html">here</a>.
- Some students may choose to continue to develop their submissions as their final project for this class. 