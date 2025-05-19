My name: Lavin Ma


### Check Your Understanding
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   Within a Github action that runs whenever code is pushed...
   I would do this because tests would be run automatically everytime code is pushed to the repository. It would be a part of a continuous integration (CI) workflow, so bugs would be caught earlier and attempting to merge broken code wouldn't happen. With this approach, as a developer, I would not have to remember to run these tests and the codebase will still remain stable.

2) Would you use an end-to-end test to check if a function is returning the correct output?
   No. E2E tests are used to simulate real user interactions with a webpage with actions such as clicking a button or navigating pages. If I want to check if a specific function is returning the correct value, using unit tests would be better because it can directly test for specific pieces of logic without needing to load the full webpage.

3) What is the difference between navigation and snapshot mode?
   Navigation mode analyzes the page directly after it loads, capturing things like the time it takes to load, performance metrics, and other parts of the user experience from beginning to end. Snapshot mode looks at the page in its current state, making it useful to detect problems affecting things like visuals or accessibility. 

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   1. We could properly size images. The report shows a potential savings of 518 KiB by reducing image dimensions. Optimizing the image size can significantly improve page load times.
   2. We could also add a `<meta name="viewport">` tag. The site is missing a viewport tag, which is essential for mobile responsiveness. Adding one will improve usability on smaller devices.
   3. We could use next-gen image formats. Serving images in newer formats can save an additional 165 KiB and improve performance (which will make a difference for individuals with slower connections).

