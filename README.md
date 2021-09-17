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
- the methods above are all array methods (meaning they do a function on arrays); .map is a way to manipulate the data in an array, without actually manipulating the original array, as .map automatically creates a new array. You could use .map if you took an array and needed to modify all the elements in the exact same way
- .filter creates a new arrray by removing elements that do not belong / meet your criteria. Let's say you only want to filter for a certain year in a dataset (e.g., data must be after 1999)
- .reduce takes all of the elements in an array and reduces them into a single value. .reduce is a good method to find the sum of a list of numbers in an array

2. Explain the difference between a callback and a higher order function.
- a higher order function is a function that takes another function as an arguement and returns a function to its callers; whereas, a callback function is a function that is passsed to another function with the expectation that the other function will call it

3. Explain what a closure is.
- closures happens when the function reaches back into its outer scope to grab something defined in the outer scope

4. Describe the four principles of the 'this' keyword.
- window binding: it happens when THIS is not given context; at that point, Javascript will return the window to us
- Implicit Binding: this is the most common principle; it essentially says when the function is invokved, look to the left of the dot when the function is invoked
- explicit binding: THIS in explicit binding is explicity passed into the argument. Within explicit binding, you have .call(), .apply(), and .bind()
- new binding: used with constructor functions and says that when a function is invoked as a constructor function, using the 'new' keyword directs THIS to the newly created object

5. Why do we need super() in an extended class?
- Super() is called to avoid duplicating the constructor parts that are common between classes that have inheritance

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

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

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

