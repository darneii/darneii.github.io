---
layout: essay
type: essay
title: Questioning Questions
date: 2020-09-10
labels:
  - Asking Questions
  - Smart
  - "Not So Smart"
---

Software engineers will come across issues from time to time. They may not always have the immediate answer to the issue, if any, and the question they have won't always be as easy as "Googling" it. Using websites such as [Stack Overflow](https://stackoverflow.com/) will be useful, and to ensure that answers received are beneficial, it is best to ask a "smart" question. There are key factors to avoid asking a "not so smart" question, so by analyzing various questions that others have asked, we are able to see the difference between the two types of questions.

## "Smart" Question

<img class="ui medium right floated rounded image" src="../images/Lightbulb.jpg">

The "smart" question I came across came from a developer who wanted to know how to [revert a file](https://stackoverflow.com/questions/215718/how-can-i-reset-or-revert-a-file-to-a-specific-revision). The developer stated that they knew what specific revision they wanted to revert to using "git log" and "git diff", but they didn't know how to do so. Because the developer provided that information, those who answered knew that they had the hash code. They were able to get straight to the point without the need to provide a lengthy explanation on how to obtain the hash code. The top answer provided just one line, along with an extra bit of information.

## "Not So Smart" Question

The "not so smart" question I came across was from a developer who wanted to know how to print out the [contents of an array using a for-loop](https://stackoverflow.com/questions/522563/accessing-the-index-in-for-loops). While they did provide code on their attempt to do so, they also asked to access the loop index from 1 to 5. Just like in Java, in Python, the index of arrays start at 0. Many of the answers (including the top rated) did not mention that factor, so if one were to use the code provided by the first answer they saw, they would see that it starts at 0 and not 1, so there may be complaints about it not starting from 1. The second answer provided code that would lead the print count to start at 1, so if one were to try to look for a fix, they would not have to look far. Had that person not provided another answer to the question, there would be those left puzzled.

After reviewing the questions amongst others on Stack Overflow, I know what to and what not to do when it comes to asking questions myself. It may take practice to get used to developing the "smart" questions, but doing so would allow answers to be more useful to not only myself, but to others who may have the same questions themselves. I would hate to see others think that even after seeing the answer and trying to utilize it, their code doesn't work properly and would lead to more problems than there needed to be. If everyone were to ask smart questions, we could avoid any issues and make more progression.
