---
title: "Designing learning environments for CS1 debugging"
date: 2024-10-29
lastmod: 2024-09-08
# tags: ["Romance languages","philology","irregular verbs","Spanish","Portuguese"]
author: "Ayse Hunt"
# description: "This graduate course presents classical results in Romance philology." 
summary: "This project explores the challenges university students face while learning to debug code. The goal of this work is to design digital tools that support students during the programming process." 
showToc: true
disableAnchoredHeadings: false

---

## Introduction

Debugging, a.k.a. the process of finding and fixing errors in your code, is difficult. Even experienced programmers struggle to resolve bugs sometimes. Debugging is notoriously difficult for new programmers to learn.

This raises the question--what about debugging makes it so challenging for new programmers? 

Debugging requires:
+ **disciplinary knowledge** (e.g. knowing how to read code, understanding how a program executes, etc.)
+ **metacognitive practices** (e.g. monitoring your understanding, help-seeking, reflecting on your understanding, etc.)
+ **complex problem solving skills** (e.g. working systematically, hypothesizing about the error's cause, etc.)

With these challenges in mind, I set out to explore how we might design a tool that supports students during the debugging process. Specifically, I was interested in exploring how a tool that could prompt students from within the coding environment might be helpful.

<!-- need image here of an ide with a little pop up saying something like "hey! consider adding a print statement to see what is happening!" -->

## Think-Aloud Study

In this study, I conducted think-aloud interviews with 14 students who had recently taken an introductory computer science course. 

I prepared a programming task for each participant to complete. My goal was to elicit debugging moments without making the task too difficult. 

During these interviews, I sat with participants and tested various low-fidelity prototypes. I frequently used a Wizard-of-Oz approach in which I would verbalize questions, ideas, or other information in an effort to prompt participants. This method allowed me to quickly get feedback on the content and type of support that participants responded to.

<!-- need image of the set up -->

## Initial Findings

The single biggest take-away from the think-aloud study was that no amount of metacognitive or problem solving support could overcome gaps in disciplinary knowledge. 

Additionally, presenting paricipants with new ideas when they are already unsure or overwhelmed was not successful. This highlights the importance of developing real-time feedback systems that consider a user's context and emotional state.

## Next Steps

As a next step for in this work, I will be interviewing experienced Computer Science faculty to better understand their strategies and approaches to teaching debugging. 

Through the results of the think-aloud study and related literature reviews, it became clear that there is a gap in the research around explicit debugging instruction and best practices. This interview study will help define the parameters for the next iteration of our debugging tool. This work is ongoing -- more to come!




