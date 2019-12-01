---
title: Operation Finish Line
draft: true
author: admin
date: 
slug: operation-finish-line
categories: [PhD]
tags: [PhD]
subtitle: ''
summary: ''
authors: []
lastmod:
featured: no
diagram: true
image: 
  caption:
  placement: 3
markup: mmark
math: true
projects: []
---
I'm rather a big fan of the show 'Gilmore Girls'! In season  7 episode 12, Paris prepares what can only be described as the most magnificent timetable in the lead up to finals. Being in the final year of my PhD, it seemed fitting to put together my own #OperationFinishLine; although, this is liekly to be subpar when compared to Paris's operation. I started my PhD in 2017 and am due to finish at the end of 2020. Like many PhD programmes, mine has had it's fair share of problems. Nonetheless, I am in the end-game and hopefully this serves as a form of motivation to stay on target.

Below is a general overview of what I have left to do... a lot I know. 
```mermaid
graph TD;
  B(Study 2)-->C(Study 3 Ethics)-->D(Study 3)-->E(WRITE!)
```
While I have this general map in mind, if I want to channel my inner Paris Geller I need a more structured plan; cue the Gantt chart. I've tried to breakdown the major remainding tasks of my PhD into more digestable ones with a given time period. This was also a good opportunity to play around with the `DiagrammeR` package in R. I am currently in the midst of data collection for my second study and therefore the Gantt chart takes off from there. Over the Christmas period I plan to draft up my final PhD research study and complete the associated ethical application. This way I can hit the ground running come January. Following approval from the University's research ethics committee, I will begin data collection. I've given myself a rather conservetive deadline for the final study and hope to have this wrapped up by June 2020. The remainder of my time will largely be dedicated to data analysis and **WRITING MY THESIS!** Currently I have some parts of my thesis written but certainly have the majority ahead of me; a joyice time. I'm not sure This is operation finish line! I still need to put some more thought into a writing plan but perhaps I will update this once I have a clearer idea.

```mermaid
gantt
  dateFormat  MM-YYYY
  axisformat  %m/%y
  title The Horrid Gantt Chart
  section Study 2
  Data Collection   :a1, 11-2019, 12-2019
  Lab Analysis      :01-2020, 03-2020
  Manuscript        :03-2020, 05-2020
  section Study 3
  Ethics Application      :12-2019, 02-2020
  Data Collection         :03-2020, 06-2020
  Lab Analysis            :07-2020, 08-2020
  Manuscript              :08-2020, 10-2020
  section Thesis
  WRITING!          :11-2019, 10-2020
  Proofing          :10-2020, 12-2020
  Submission        :12-2020, 01-2021
  Viva Voce         :01-2021, 02-2021
```
