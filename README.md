# What Is Code Testing

*`updated 21 April 2022`*

I was too intimidated by the concept 
of code testing. Why
will you test your code in the first place? Do
you not trust your own code? Will it
not work as intended?

But then by reading so much about this, I fully
got the hang of it. So here it goes:

Without the automated code testing,
the tendency is to test
your code by running the entire program and
manually testing it. So, you are still testing
it without being aware of it.

For example, for students doing programming 
in Robotics, since their focus is just to know
whether their code is actually working,
they will be manually running the code
from time to time. If the code did not
work as intended, then they will trace
the problem. This entire process
is being repeated and is actually time
consuming particularly when the code
is getting longer and longer. And take
note, it is not yet one big project.
But testing is already there, they are 
just doing it manually.

## Why Code Testing
As was mentioned from my example,
if you don't have any idea about
code testing, well I say,
you are doing it
without being aware of it.
The tendency is to
run the whole program and manually 
test whether each part of the 
code is working as intended.

Now, this is only practical if your
project is just a small one. But
software development nowadays 
is already a very sophisticated one.
So, testing it manually will surely
be a headache. Plus, it
is not that efficient.
And even a well-tested code will not
always work as intended to be.
Our role is just to minimize errors and 
maintain the code.

## Debugging Vs Code Testing
Others are really confused about these two
things, are you testing while you are debugging?
Or conversely, are you debugging while you are
testing?

Debugging was a popular practice before
the term `code testing` was coined. And yes,
developers back then manually test
their code. And they
were referring to testing as part of
debugging, without, of course, the knowledge
of it. But there came a time, 
it was recognized as a separate process.
And of course, software development
has been continuously evolving, testing
now is a very sophisticated one: there 
are technologies just for testing alone.

So testing now becomes the way to actually
look for system errors and debugging is 
the process of solving these errors.
Hence, debugging
is a manual task to be done by a talented
debugger or the developer himself while
testing, the act of finding errors, is
mostly automated through coding. 
By making testing
an automated one, you save time and effort, 
since you don't need to run the entire
program just to see whether your code
is working as it is intended to be.

## Unit Tests And Integration Tests
Unit tests and integration tests are the most
common tests that are being referred to
mainly because these two tests should be done
(most of the time) by 
the developer himself.

There are on-going debates as to
what is considered a unit, say,
it can be a component of a program
and whether you test first before
you code and whether every line
of code should be tested. 
Of course, development is up 
to the programmer or the company
in what they believe is the 
best for them. 

Integration tests, on the other
hand, are tests when you are 
combining several components:
will they still work as intended?
Problems arise when there
is too much dependence in
a program. So mainly, even
testing is just in your mind,
it will affect the way you
use global variables and 
components that are dependent
on one another.

For me, personally, I write
unit tests and integration 
tests for my projects. 

In my experience, 
I had developed the projects
first without any idea about
code testing. 
So I wrote them backwards. 
With that, I refactored
everything in such a way that:

1. a function will
return just one value
2. components should not
be dependent on any other
part of the program, if
the developer can avoid
it
3. return values should
be handled by arguments
and should be returned
properly (remember, rule
no. 2)
4. global variables should
be used minimally and 
should be closely monitored
5. throwing exceptions
should be closely monitored
through testing because
throwing exceptions are actually
tricky

Then, the effect was immediate
the very first time I did this:
when I looked at the code, it was
really neat. 

So, from that point in time,
I realized I need to 
include code testing in my
workflow. But I just write unit 
tests for components or functions that
I feel I really need to focus on.

This only means that a developer
should not find it difficult to
write unit and integration tests,
if he/she finds it difficult,
the source code is really not
that neat.

But others will still insist, they are
good and excellent coders and very
careful writing quality code. I
say I had the same feeling but
even if you just started thinking
whether your code is testable,
you will have a different approach.
You will see things in a different
perspective.
It's just like you looking at your
work just like other persons in charge
of checking your code. Remember that
others see errors better than
ourselves.

Other tests just like black box
testing will be done by another person,
usually a tester. This is another
layer of testing for quality assurance.
Don't you know that bugs can cause
million dollars to be just wasted?
So, a company really needs this kind
of quality assurance.

You can check out my actual codes with
unit and integration tests:

<https://github.com/jdevstatic/java>

## Useful And Valid Links
Here are the detailed tutorials for this code testing:

<https://www.toptal.com/qa/how-to-write-testable-code-and-why-it-matters>

<https://www.zeolearn.com/magazine/what-is-code-testing-and-why-is-it-important>

<https://www3.ntu.edu.sg/home/ehchua/programming/java/JavaUnitTesting.html>
 
<https://www.geeksforgeeks.org/differences-between-black-box-testing-vs-white-box-testing/#:~:text=Black%20Box%20Testing%20is%20a,is%20known%20to%20the%20tester.> 

<https://www.geeksforgeeks.org/differences-between-testing-and-debugging/#:~:text=Testing%20is%20the%20process%20to,the%20failure%20of%20implemented%20code.&text=Debugging%20is%20done%20by%20either%20programmer%20or%20developer.>
