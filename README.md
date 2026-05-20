# CSE 110 Lab 7

### Names : Jacky Yu

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**within a GitHub Action that runs whenever code is pushed**
This is the best option because it automatically checks whether new changes break existing functionality before the code is merged or used by other team members. It also makes testing consistent, since everyone’s code is tested the same way instead of relying on each person to remember to run tests locally.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)

**No.** End-to-end tests are meant to test a full user workflow from start to finish, such as clicking buttons, interacting with the webpage, and checking that the UI behaves correctly. To check whether a single function returns the correct output, I would use a unit test instead.

![Screenshot of test results](./ss.jpg)
