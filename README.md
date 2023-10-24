# ECE444-F2023-Lab5

Implemented based on this repo: https://github.com/mjhea0/flaskr-tdd#database-setup


### Pros and Cons of TDD

Research taken from [this article](https://medium.com/javarevisited/the-pros-and-cons-of-tdd-in-software-development-bc65ec3bcc76).

### Example test case 

This is an example testcase from our user project attached [here](https://github.com/ECE444-2023Fall/project-1-web-application-design-group16-fieryflamingos/blob/05c77bb487300e3da111578b249a82917f649b4f/tests/test_db.py#L107).

If this link no longer works, the branch we were working on tests on probably got merged.
Please look for it here: https://github.com/ECE444-2023Fall/project-1-web-application-design-group16-fieryflamingos/tree/main
under tests/test_db.py
Search for the comment with my name: Dylan Sun, which should bring you to the line which starts the unit test written as an example for this lab. 

**Advantages:**

One of the advantages of TDD is that it promotes good software design. The process of writing tests first forces the developer to think about the functionality and design of the code, leading to more well-designed and modular code.

TDD also increases code coverage, meaning that more lines of code are tested, reducing the risk of bugs and other issues. Another advantage of TDD is that it makes the development process faster and more efficient. The tests serve as a form of documentation, allowing developers to quickly see what the code is supposed to do. This saves time compared to manually testing the code and can also lead to more consistent and reliable testing. Additionally, TDD makes it easier to catch bugs early in the development process, before they become bigger and more expensive to fix.

**Disadvantages:**

However, TDD also has some disadvantages. One of the main disadvantages is that it can slow down the development process, as the developer needs to write the tests first before writing the code. This can be especially challenging for more complex or unfamiliar code.

TDD can also be difficult to implement in an existing codebase, as it requires a significant shift in the development process and mindset. Another disadvantage is that TDD can result in over-testing, where the tests are written for every possible scenario, resulting in a large and complex test suite. This can make it difficult to maintain the tests, as well as make it harder to understand the tests and their results.
