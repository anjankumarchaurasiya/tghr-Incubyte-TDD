# String Calculator

This project implements a string calculator that processes a string of numbers and performs addition. The calculator supports various features such as custom delimiters and handles errors for negative numbers. It is built using JavaScript and tested using Jest.

## Introduction

The String Calculator project provides a simple way to perform addition on numbers provided as a string. It supports:
- Basic addition of comma-separated numbers.
- Handling newlines as delimiters.
- Custom delimiters.
- Error handling for negative numbers.

## Run Project

To run this project, ensure you have the following installed:
- **Node.js**: A JavaScript runtime environment.
- **npm**: Node Package Manager (comes with Node.js).

Download Node.js from [nodejs.org](https://nodejs.org/). npm will be installed automatically with Node.js.

## Installation

 **Clone the Repository**

   Open a terminal or command prompt and execute:

  - git clone <repository-url>
  - cd <repository-directory>

## Install Dependencies
- npm install

## Run Tests
- npm test

## Run the Code
 
  **Build the Project** 
    - npm run build
  **Run the Compiled Code**  
    - node dist/index.js

## Modify the code

 **Edit the Code** 
    You can modify the main logic in the index.ts file located in the root directory and the stringCalculator.ts file located in the src folder.

 **Rebuild After Changes**
    After making changes, rebuild the project to see the effects:
    - npm run build
 **Rerun Tests**
    - npm test


## **Output of - (npm test)** 

   PASS  tests/stringCalculator.test.ts
    Test Suite        | Test Case                                             | Result | Time
   -------------------------------------------------------------------------------------------
   String Calculator | should return 0 for an empty string                   | Passed | 6 ms
   String Calculator | should return the number itself for a single number    | Passed | 1 ms
   String Calculator | should return the sum of two numbers                  | Passed | 1 ms
   String Calculator | should return the sum of multiple numbers             | Passed | 1 ms
   String Calculator | should handle newlines as delimiters                  | Passed | 
   String Calculator | should support custom delimiters                      | Passed | 
   String Calculator | should throw an error for negative numbers            | Passed | 21 ms
   String Calculator | should show all negative numbers in the error message | Passed | 2 ms
   
   ------------------------------------------------------------
   | Metric       | Result                                      |
   ------------------------------------------------------------
   | Test Suites  | 1 passed, 1 total                           |
   | Tests        | 8 passed, 8 total                           |
   | Snapshots    | 0 total                                     |
   | Time         | 4.904 s, estimated 6 s                      |
   | Status       | Ran all test suites                         |
   ------------------------------------------------------------

