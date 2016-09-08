#Functions Self Assessment

## Guidelines

- You should be able to finish this self assessment in about an hour.

- Self-assessments are meant to give you an idea of how well you understand--or can figure out--the material that you covered recently.

- What you see is what you get--most of the time we don't include outside libraries.

- WARNING NO TESTS: As you can see, we haven't provided any tests. This is so that you can practice debugging without them. Copy and paste your code into your Chrome Console for a quick and easy way to test your code.


## Grading Outline

Functions Self Assessment : 

## Self-Grading Process

After you complete each prompt, assign a grade to each item in the above Grading Outline, using this Grading Scale:

### Self-Assessment Grading Scale:

Qualitative grade | Meaning
---|---
Complete             | You believe your solution to be fully complete and meeting the specified requirements.
Mostly complete      | Your solution is well on its way to being complete, but you ran out of time or can't remember exactly how to do *one* particular aspect. You believe anyone who understands the problem well would endorse your solution as the right one, and know pretty clearly how to finish up any last touches.
Significant progress | You have the right idea and were heading in a good direction. Covers everything between Mostly Complete and Attempted.
Attempted            | You were very challenged by the prompt and had trouble making any significant progress on the problem, but wrote at least one meaningful line of code that appears to be a genuine attempt.
Not attempted        | Whether you've thought much about the problem or not, you have no lines of code to show for the problem. (Note, you should avoid ever getting into a situation where this is the grade you'd give yourself. Make a passing attempt at each problem before going back to complete any one problem.)

#### Example Submission:

Objects: COMPLETE  
Arrays: ATTEMPTED  
Functions: SIGNIFICANT PROGRESS  


### Starting every problem

You are expected to at least start every problem. As with any test, you make the most progress in the first few moments of work on each question, and we don't want you losing out on credit you could collect just because you get fixated on one or two questions. Do an initial pass to get the easiest answers out of your system, then go back and improve anything you can.


## Submitting Solutions

**VERY IMPORTANT: Before submitting your solutions, find and fix all syntax errors**

Solutions are submitted via pushing your code to your OWN FORKED repository. We will take it from there.

##Instructions :
**We have defined an array variable `myArray` for you in the JS file. Do not replace it with the examples below**

### printAll()
* [ ] create a function called "printAll" that takes an array as an argument
* [ ] in this function, create a proper for loop that prints out each element of the array

Example:
```javascript
myArray = ["These", "are", "the", 7, "values", "of", "myArray"];
printAll(myArray);
/* Result :
These
are
the
7
values
of
myArray
*/
```

### longArray()
* [ ] create a function called "longArray" that takes an array as an argument.
* [ ] this function returns `true` if the array has 7 or more elements. Otherwise, it returns `false`.

Example:
```javascript
myArray = ["abc", 2, "three", 4, true, false, true];
longArray(myArray); //true
```

### countNums()
* [ ] create a function called "countNums" that takes an array as an argument
* [ ] in this function, declare a "counter" variable and set it to 0.  
* [ ] create a proper for loop that checks the `typeof` each element.
* [ ] if the element is a `number`, incrememt a counter variable.
* [ ] return the counter

Example:
```javascript
myArray = [10, 24, 32, true, "Kanye"];
countNums(myArray); //3;
```
