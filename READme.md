#Exercises for WWC East Bay Problemset

[JS FIDDLE](https://jsfiddle.net/sdawkz2t/)

Welcome to our first Women who Code East Bay Algorithms Prep.  Each week we will tackle a different common Algorithm/ Data Structure.

Feel free to work with a partner on these problems.  And we will come back to share our solutions.  

##Monday, Nov 14th -Recursion

###What is Recursion?
  It is simply when a function calls it self. 
  
![cat-recursion](https://cloud.githubusercontent.com/assets/10103582/20289242/a75498be-aa8d-11e6-8b93-9e13292f27d0.gif)
  
###Where do you see it?
1. Recursive Functions (Any function that calls itself)
2. Recursive Algorithms (ex. Sorting Algorithms)
3. Recursive Data Structures (ex.Trees -- trees that are composed into smaller trees and etc...)

###Why Recurison?
  - Provides an elegant solution to key your code D.R.Y.(Don't Repeat Yourself) 
  - Basic/Expected CS knowledge!
  
###How do we tackle a recursive problem?
<hr>

First we need to understand that happens when a function calls itself:

![hello](https://cloud.githubusercontent.com/assets/10103582/20289013/483ea0f0-aa8c-11e6-9be6-a708f4cbc01a.png)

![max](https://cloud.githubusercontent.com/assets/10103582/20289052/5dd3c026-aa8c-11e6-90d9-01cb6deceb98.png)

We can see in this example that the function hello() is calling itself and it is excuting itself infinitely.


####What do we need to do in order for us to stop it?

We need to provide some way for us to BREAK it or RETURN a VALUE.
This in other words this is called a `base case`:

![hello2](https://cloud.githubusercontent.com/assets/10103582/20289016/49ec5fb4-aa8c-11e6-8c43-98d693fd0f7d.png)

####Procedure:

1. Identify the Base Case
2. Identify the Recursive Case
3. Return where appropriate
4. Write procedures for each case that brings you closer to the base case
 

##Problems-- (You should use recursion for all of these):
1. Intro to Recursion: (easy)

 - [Intro to Recursion](https://github.com/chylaudes/WWCEastBay-AlgosPrep/blob/master/11-14-16/problemset/introToRecursion.js)

2. Reversing a String (easy)

 - [Reversing a String](https://github.com/chylaudes/WWCEastBay-AlgosPrep/blob/master/11-14-16/problemset/reversingAString.js)

3. Factorial(easy)

 - [Factorial](https://github.com/chylaudes/WWCEastBay-AlgosPrep/blob/master/11-14-16/problemset/factorial.js)

3. Fibonacci Sequence (easy - med)
 
 - [Fibonacci](https://github.com/chylaudes/WWCEastBay-AlgosPrep/blob/master/11-14-16/problemset/fib.js)

4. Greatest Common Denominator (med - hard)

 - [Greatest Common Denominator](https://github.com/chylaudes/WWCEastBay-AlgosPrep/blob/master/11-14-16/problemset/gcd.js)

5. Permutations (med - hard)

 - [Permutations](https://github.com/chylaudes/WWCEastBay-AlgosPrep/blob/master/11-14-16/problemset/permutations.js)

####Extra Resources:

[Call Stack](https://www.youtube.com/watch?v=beqqGIdabrE&t=2s)

[CS50- Recursion](https://www.youtube.com/watch?v=VrrnjYgDBEk)

##Finished?
CONGRATS!! Give yourself a pat on the back, you must be super comfortable with recursion!

![Nailed](https://cloud.githubusercontent.com/assets/10103582/20289011/44adadaa-aa8c-11e6-9955-5ac861860ba7.gif)

Feel free to look at the Women Who Code San Francisco Interview problems to practice more!

[Women Who Code White Boarding problems](http://meetupresources.herokuapp.com/whiteboard.html)

**AND**

Make a Pull Request to share your code! :)

##Exit Ticket!

Before you leave, please fill out this exit ticket to give us feedback on what you would like to see in the next session!


[EXIT TICKET](https://goo.gl/forms/i4JicdTtAl2RWkeg2)


##Looking for Volunteers!

If you guys are interested in Volunteering for WWC East Bay Algorithms Prep:

Please email: **chylau.design@gmail.com**  with the subject line **"Interested in Volunteering--WWC East Bay AlgosPrep"** and write a short blurb about yourself, your programming experience, and why you would love to volunteer!  


**Disclaimer:**
Most of the material I've used is a combination of workshop classes that I've taken in the past.  I cannot take credit for the things here.  Programs that have contributed to this repo:  General Assembly, Frontend Masters/ Telegraph Academy-@bgando  
