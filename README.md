
# [Tribute Page](https://github.com/SchoolOfCode/w0d0_precourse-challenge-amritatwal)

**Table of Contents**

1. [Summary](#summary) 
2. [Context](#context) 
3. [Reflection](#reflection) 
4. [Takeaways](#takeaways) 


## Summary

This is a tribute page I have created for FreeCodeCamp’s Responsive Web Design certification. In this project I pay tribute to Chelsea Women's forward Fran Kirby.  

## Context

This tribute page was intended to:

- Fulfill the intended user stories
- Input my learning so far and some of my own creativity 

Instead of choosing to shed light on one of Chelsea's male footballers, I chose Fran as the subject of this tribute instead, hoping to challenge my own instincts when it comes to showing appreciation of the incredible amount of talent seen at the club I support. 

## Reflection 

When taking the opportunity to reflect on what I learnt when creating this page, what stands out as a beginner was the power (_and fiddly-ness!_) of CSS Grid to create responsive layouts and the importance of semantics in HTML. 

For instance, I found CSS Grid quite tricky to work with as I encountered problems trying to get images (of different sizes) to fill in the space and resize responsively. There was also a good learning experience in mastering the container formatting and ensuring correctly set-up columns and rows for this particular set-up.

  ```
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  ````

  and how that impacts one of its children

  ```
  grid-column: 2 / 3;
  grid-row: 1 / 4;
  ```

Three rows are defined in the parent container but due to how grid tracks work - lines that represent the _start_ of the track - the grid rows set for the `#tribute-info` child needs to start from 1 to _4_. 
  
Semantics wise it was good practice to incorporate what I learnt [here](https://marksheet.io/html-semantics.html). Every tag I choose has importance and meaning in the document. When reflecting on whether the use of `<strong>` was appropriate for the honours titles, I deemed it more fitting to use `<b>` instead. Although it may not be so black and white, I think it is good to get into the habit of thinking about what weight and purpose we give to text.  

## Takeaways  

The pre-course learning so far has been really fun! This project was a great way to put together 
what I have learnt and use my creativity to build something that fuses together two interests of mine - coding and football. There is definitely a mental strain to push through when faced with
elements or styling not behaving the way they are intended to, but it makes the progress even more worthwhile. I have enjoyed the tweaking around and debugging to not only ensure the tribute page works correctly but to experiment and explore. I am extremely excited to learn more and to keep building bigger and better projects! I look forward to be able to eventually add more complex styling and eventually some JavaScript. 
