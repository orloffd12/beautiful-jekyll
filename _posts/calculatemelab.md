---
layout: Blog post
title: Calculate Me Lab - David O 
---

# Calculate Me Lab Blog Entry
## David Orloff
### Due 11/08/20

* Here was my process in creating this lab: 

In order to begin this lab, I needed to understand how postfix works.  
In order to do this, I solved some postfix problems on my own to familiarize myself with it.  
The next thing I needed to do was to create a Stack class that I would be able to run in order to  
solve postfix.  I decided to use a stack because it allows me to pop and push different values  
in a way that makes it very easy and efficient to solve postfix. I implemented the stack  
class by checking each character in each row - if it was a multiplication, addition, or  
subtraction sign then I would store it and pop the last two numbers out of the stack  
and apply the operator on those two values.  
In this lab, I understood the concepts that I needed to apply but I found it hard to  
actually code it as I had many syntax issues throughout. However, I tried to figure  
out the most efficient way of coding this and I was eventually able to resolve the issues that  
I had. Once I got everything to work, I realized that all of the answers were incorrect.  
However, I realized that when I was subtracting values, I would subtract the second value I  
popped out of the stack from the first value, instead of subtracting the  
first value from the second value which was causing all of the answers to be completely  
incorrect. Although the fix was extremely simple(changing it from a - b to b - a), it made a    significant difference in the results.    