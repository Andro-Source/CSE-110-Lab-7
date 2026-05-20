# CSE 110 Lab 7

### Names : Jacky Yu

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**within a GitHub Action that runs whenever code is pushed**
This is the best option because it automatically checks whether new changes break existing functionality before the code is merged or used by other team members. It also makes testing consistent, since everyone’s code is tested the same way instead of relying on each person to remember to run tests locally.
