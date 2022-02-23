## Intro to C++ I Lab 07

Doubling

**Date assigned:** 

**Program due:**

**Points:** 

**This is an individual assignment.**

**Goals:**

1.  Use a for loop

2.  Understand exponential growth

3.  Process data from a file with sentinel value


**Lab 7.1**

Write a complete C++ program in a project called **Money** that will
determine whether you'd prefer to be paid \$1,000.00 a day for 25 days
or a penny the first day, two pennies the second, four pennies the third
day and so on, doubling the amount you made the previous day. There is
no user input to this program.

The x's should be replaced by the doubling amount on the 25^th^ day and
the total after summing all of the doubling amounts:

<pre>
*** Makin' Money ***

Day     Thousands     Doubling
  1       1000.00         0.01
  2       1000.00         0.02

**And so on until you reach the 25th day**

 25       1000.00      xxxx.xx

Total    25000.00      xxxx.xx
</pre>


**Lab 7.2**

A data file **grades.txt** contains an unknown number of quiz grades
with a sentinel value of -99.0. Write a complete C++ program in a
project called **Grader** that computes and prints the average of all
quiz grades after dropping the lowest grade. As an example, if the data
file contains the following values:

<pre>
15
16
17
16
15
0
19
20
14
15

You are to print the following:

*** Quiz Grader ***

Average after dropping 0 is: 16.33
</pre>

**To complete this assignment you must submit the following:**

1.  **An electronic Solution of your program on GitHub**

    a.  You are to click on the Lab07 Link on The C++ Tutorials in the section Data Input to accept this
        assignment as we've done before. Once accepted, code up a
        complete solution to each project specified above. Your
        complete solution is to be pushed to GitHub no later than the
        date and time specified above for your specific section. I will
        only grade your solution from the proper location on GitHub.

    b.  Pay attention to the example output above. Your program's output
        must look **exactly** like the example output! The spacing and
        newlines in your output must match exactly.

    c.  Make sure that your program compiles and runs correctly with no
        errors and no warnings. If you get any errors, double check that
        you typed everything correctly. Be aware that C++ is
        case-sensitive.

2.  **An electronic pdf (punetidLab07Doubling.pdf) 
of your program is to be emailed to ryandj@pacificu.edu**
