---
layout: Blog post
title: Hospital Lab - David O
---

# HospitalLab Blog Entry
## David Orloff

* Here was my process in creating this lab:   
  
    * I first created a method to get the text file. I assigned a variable called "lines"  
      to the method in order to be able to check and modify each line of the text file.

    * Next, I made a method to iterate through the csv and print each line of text.  
      I used one while loop and on for loop to do this. I used the while loop to check  
      the text for errors and the for loop as the loop that would print the text.
    * After that, I called the method that would print out the text file and then   
      piped the text file into a csv using the terminal and the command: 
      python3 hospitallab.py > hospital.csv.  
    * I then worked with Alex Gerstenhaber to create a file that would clean the csv. 
    * To clean the csv, we needed to put everything into the same units.  To do this, 
      we had to change beds per 500 people to beds per 1000 people, and beds per 2000  
      people to beds per 1000 people. By doing this, the information in the lab was much  
      easier to analyze and compare.
* Issues 
    * The first issue that I had was in the original hospital lab file.  
      I wasn't able to change the value of the lines variable in my second  
      method, but Ethan told me that I had to call the global keyword  
      in order to be able to modify lines outside of the method / class / file.  
    * The second issue I had was a minor one that Mr. Lee explained to me very quickly.  
      When I was trying to print the csv only one line (or no lines) would print.  
      I realized that I had to call the allVals method in order for the entire thing  
      to print. 
* What could have gone better
    * I think that when cleaning the csv file, it could have been a bit less  
    hard-coded. There is definitely a way to make it so that the program will identify  
    the most common type of "beds per person" in the file and then convert all of the 
    "beds per person's" to that unit of measurement as well as the beds values without stating any specific values.  
   
