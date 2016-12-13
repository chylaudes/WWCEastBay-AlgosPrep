#Exercises for WWC East Bay Problemset

Welcome to Women who Code East Bay Algorithms Prep.  Each week we will tackle a different common Algorithm/ Data Structure.

[JS FIDDLE](https://jsfiddle.net/sdawkz2t/#&togetherjs=3sLLDkEoK1)

Welcome to our first Women who Code East Bay Algorithms Prep.  Each week we will tackle a different common Algorithm/ Data Structure.

Feel free to work with a partner on these problems.  And we will come back to share our solutions.  

##Monday, Dec 12th -Sorting


##Warm-up

Do these with recursion!

1. Reversing a String (easy)
[Reversing a String](https://github.com/chylaudes/WWCEastBay-AlgosPrep/blob/master/11-14-16/problemset/reversingAString.js)

2. Greatest Common Denominator (med - hard)
[Greatest Common Denominator](https://github.com/chylaudes/WWCEastBay-AlgosPrep/blob/master/11-14-16/problemset/gcd.js)

##Sorting Algorithms

Before we go over Sorting Algorithms, we should atleast cover some important concepts of Space and Time Complexity.

##Space and Time Complexity

Space and Time Complexity is what we use to measure how optimized and fast an Algorithm is.

####Space Complexity:  

*	How much memory is it taking up?

####Time Complexity:

* How many comparisons are made?
* How many swaps are made?
* As your data set grows how much more work your algorithms is going to do?

...with respect to input size

...and assuming worst case scenarios



##EXAMPLE:

Let's say we have an algorithm heavy website like Zappos and a PM asks us to build a feature to look for the most expensive pair of running shoes and the least expensive pair or running shooes

[Picture here]



Let's write an algorithm to do the job!

So we have this data...


[Picture here]


We'd expect that the more data we have, the longer it will take to figure out the min and max required for the range.  However, as our dataset grows, the cost can grow really fast or slow!


#####One Approach is to compare every number to all the other numbers...

* How many opperations/comparisons would we have to make if we had 4, 10, 200?



#####Second Approach what if we just checked for the highest number and for the lower number?

* How many opperations/comparisons would we have to make if we had 4, 10, 200?

#####What if the data is already sorted?

[Picture here]


* How many opperations/comparisons would we have to make if we had 4, 10, 200?

FAST


Here's a quick table of Big O Notation:

[PICTURE OF TABLE]


Big O Table:

[table]

Was the input increases what happens?


###Problem Set

Elementary Sorting:

1. Bubble Sort

	[Picture of Bubble Sort Algorithm]

	Is a comparison sort that repeatedly swaps adjacent elements that are out of order

2. Merge Sort

	Divide and Conquer Algorithm

3. Quick Sort (if time!)

##Finished?
CONGRATS!! Give yourself a pat on the back, you must be super comfortable with recursion!

![Nailed](https://cloud.githubusercontent.com/assets/10103582/20289011/44adadaa-aa8c-11e6-9955-5ac861860ba7.gif)

Feel free to look at the Women Who Code San Francisco Interview problems to practice more!

[Women Who Code White Boarding problems](http://meetupresources.herokuapp.com/whiteboard.html)


##Exit Ticket!

Before you leave, please fill out this exit ticket to give us feedback on what you would like to see in the next session!


[EXIT TICKET](https://goo.gl/forms/i4JicdTtAl2RWkeg2)


##Looking for Volunteers!

If you guys are interested in Volunteering for WWC East Bay Algorithms Prep:

Please email: **chylau.design@gmail.com**  with the subject line **"Interested in Volunteering--WWC East Bay AlgosPrep"** and write a short blurb about yourself, your programming experience, and why you would love to volunteer!  


**Disclaimer:**
Most of the material I've used is a combination of workshop classes that I've taken in the past.  I cannot take credit for the things here.  Programs that have contributed to this repo:  General Assembly, Frontend Masters/ Telegraph Academy-@bgando  
