# ECE444-F2022-Lab6
## What are the pros and cons of TDD?
Test-Driven Development is a development methodology that includes pragamatic practises during the design/development phase of the application. These practises include (1) *writing a unit test* that covers the expected behaviour of a single feature (without considering optimality), then (2) writing and *running the production code* through the test case, which, in most cases, will fail at the first round. Assuming the test cases fail, the developer will (3) *correct/revise the code*. Once all tests pass, then we will consider (4) *refactoring* the code for any redundancy and other perfomance heuristics.

The pros of this are:
1. *Modularity*. Since we draft tests for the associated feature that focuses soley on a single functionality, we are implementing modular code. The 
2. *Better Test Coverage*. Because we consider the functionality of the feature from the beginning design process and we write the associated unit test for a feature., our tests are focused on covering the neccessary function of the code. 
3. *Additional Code Documentation*. The tests do a good job of outlining how the code should work, increasing the understanding of the code for other developers and future testers.

The cons of this are:
1. *TDD can slow the development process/Features takes longer to develop*. When the product needs to be launched quickly, then TDD can be a time consuming process. Writing a test on top of writing the implementation code can lead to longer development times. . For short term projects, ranging a few sprints, it can seem like more work than neccessary, but for larger project which are projects that involve double digit sprints, a tech company, Forte Group found that the quality, budget, and speed perspective benefitted more. [link!](https://fortegrp.com/test-driven-development-benefits/#:~:text=Fewer%20bugs%20and%20errors%20are,quality%20of%20the%20final%20product.)
2. *TDD can be difficult to maintain*. If the requirements change for a project, then the previous unit test cases written need tto be updated, whiches increases the time spent to integrate a new change to maintain the project. 
3. *Everyone needs to be aware of what practises to adhere to*. Everyone should know what is expected when using TDD. Since TDD begins before code implementation, it can influence code planning, so everyone needs to understand to adhere to the methodologies associated with TDD.

## Project Setup
$ python3.10 -m venv env
$ source env/bin/activate
(env$

(env)$ pip install flask==2.1.1

While the Python standard library comes with a unit testing framework called ùnittest, pytest is the go-to testing framework for testing Python code.

Install it:
(env)$ pip install pytest==7.1.2

## Run Heroku App
`heroku open`
