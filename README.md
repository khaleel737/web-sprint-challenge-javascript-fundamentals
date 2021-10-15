# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

.filter: filter executes a callback and checks if the element is true or false, if the element is true it returns it in the returned array and if its false it will exclude it from the results.

.map: map is similar to foreach and filter, yet it takes the array and generates the desired array through its callback function and returns it in a new array on top of the resulting array.

.reduce: reduce takes a call back and two parameters, it takes the sum and accumulator, it sums up the values from the array through a call back and reduces the numbers to 1 number by taking two parameters as arguments, first parameter is the item and the second is the accumulator that returns the sum of the array desired.


2. Explain the difference between a callback and a higher order function.

A higher order function is a function that takes other functions as arguments and returns the function its being executed to by using other function above it as its in a lexical scope context.

A callback function is a function that is called upon through passing it within its callback function.

3. Explain what a closure is.

A closure is the combination of a function combined within the same scope (enclosed scope) that execute within their lexical context.(lexical environment).


4. Describe the four principles of the 'this' keyword.

1. Implicit Binding: when a function is invoked in an Object using the dot notation.
2. Explicit Binding: when you force a function to use certain objects through .call(), .bind() and pass in the required objects as parameters.
3. new Binding: when you return a new bound function from the existing function, when executed it will return the new function with the context of the called function.
4. Lexical Binding: is when a function is called from a nested function to pass in arguments, parameters or any context to be returned, mostly used in nested functions, nested functions can access outside functions but outside functions cant access nested functions variables, etc.


5. Why do we need super() in an extended class?

super is used to call constructors, properties, methods, etc of a parent class.


You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
