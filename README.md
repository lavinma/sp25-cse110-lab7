
### Check Your Understanding
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   Within a Github action that runs whenever code is pushed...
   I would do this because tests would be run automatically everytime code is pushed to the repository. It would be a part of a continuous integration (CI) workflow, so bugs would be caught earlier and attempting to merge broken code wouldn't happen. With this approach, as a developer, I would not have to remember to run these tests and the codebase will still remain stable.

2) Would you use an end-to-end test to check if a function is returning the correct output?
   No. E2E tests are used to simulate real user interactions with a webpage with actions such as clicking a button or navigating pages. If I want to check if a specific function is returning the correct value, using unit tests would be better because it can directly test for specific pieces of logic without needing to load the full webpage.

3) What is the difference between navigation and snapshot mode?
   Navigation mode analyzes the page directly after it loads

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

