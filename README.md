# meal-planner-project
Flask app created for CS50 final project

For my first-ever project, I created a meal planner web app. It’s something I find useful, since I like to plan out what I will cook a few days in advance to help plan for grocery shopping.

What it does:
The meal planner app allows you to type in what meals you plan to have this week, along with (optionally) the key ingredients they need and a link to the recipe, if any. The data is saved to a SQL database and auto-loaded upon sign-in. The user can also keep track of what ingredients they have on hand, with functionality for adding and deleting. Ingredients are also stored in a SQL database for the user. Since each user’s meal plans are unique, the app requires users to create an account and be logged in before they can create a meal plan.

I created this app using Flask using the concepts I learned in CS50, supplemented by substantive online research. My project consists of an app.py file (with 5 routes), 5 HTML pages, and a styles.css file. I have a ‘layout.html’ file that contains the header and footer, which is extended in my other HTML files.

## Aug. 2021 Update:
After learning a lot more about front-end development since the time of making this, I've rewritten much of the HTML, CSS, and JavaScript. Instead of jQuery I have changed it to Vanilla JS with the Fetch API.