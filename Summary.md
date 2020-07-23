# AWS Machine Learning Foundations Course

## Summary Author: Pablo Nunes

----

## Welcome

- This course is divided in four parts:
  - Software Engineering Practices: Writing Code
  - Software Engineering Practices: Test and Log Code
  - Object-Oriented Programming
  - Introduction to Machine Learning on AWS

- How to succeed?
  - How to plan?
    - Define a learning path
    - Define Goals
      - Goal could be to learn
    - Keep goals in mind
    - Set short and long term goals
    - Create a incremental plan
  - Accountability - Keep yourself accountable
    - Set calendars to yourself, to goals
    - Enroll with a buddy
    - Make learning a habit
    - Remember your a larger goal
    - Have rewards after reaching the goal
  - Learning Strategies
    - Break the code into pseudocode
    - Be patient with yourself
    - Remeber your goals
  - Techincal Advice
    - Coding requires debugging
      - Read your error messages
    - Seek solutions
    - Look at successful examples
    - Build code incrementally

## Software Engineering Practices: Writing Code

- Good programming pratices:
  - Keep in mind, your code will be **production code**, and you should be careful of its quality, realiable and efficient.

  - Writing code that is **clean** and **modular**
    - **Clean**: Readable, Simple and Concise.
    - **Modular**: Could be broken up into functions and modules.
  - Splitting your code into modules(files), allows you to find relevant pieces of code, quickly. Improving readability.

  - Refactoring Code
    - When you first write code, your first idea is to prioritize what works instead of being efficient.
    - It is important, when the first model is built, you should **refactor** your code.
      - Refactoring: **Restructuring** code to improve internal structure without changing external functionality.
    - Why to Refactor?
      - Reduce workload in the long run
      - Easier to mantain code
      - Reuse more code
      - Become a better developer
    - Use Meaningful Names
      - Be descriptive and imply types:
        - In booleans use prefix, ```is_``` or ```has_```
      - Be consistent but differentiate
      - Don't make names too big
      - Use whitespace properly
      - Use PEP 8

  - Writing Modular Code
    - Use the DRY principle
    - Abstract the logic to improve readability
    - Minimize the number of entities
    - Functions should do one thing
    - Arbitrary variable names can be more effective in some functions
    - Try to use fewer than three arguments in a function
