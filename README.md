# SDET Technical Test: WIP ⚠ - To be edited and formatted

Welcome to the Software Development Engineer in Test technical test!

This test consists of two parts: while this repo lists the second part, the first one can be found [here](https://github.com/CMProductions/pqe-technical-test). It is not required but if you want, you can automate the API testing task of the first part.

You can solve the problems in whatever order you prefer.


Task 1 (SQL):

Given the following tables:

users;

user_id username

1 John Doe

2 Jane Don

3 Alice Jones

4 Lisa Romero

training_details;

user_training_id user_id training_id training_date

1 1 1 "2015-08-02"

2 2 1 "2015-08-03"

3 3 2 "2015-08-02"

4 4 2 "2015-08-04"

5 2 2 "2015-08-03"

6 1 1 "2015-08-02"

7 3 2 "2015-08-04"

8 4 3 "2015-08-03"

9 1 4 "2015-08-03"

10 3 1 "2015-08-02"

11 4 2 "2015-08-04"

12 3 2 "2015-08-02"

13 1 1 "2015-08-02"

14 4 3 "2015-08-03"

Write a query to get the list of users who took a training lesson more than once in the same day, grouped by user and training lesson, each ordered from the most recent lesson date to oldest date.


Task 2 (Linux):
How would you:
- SSH into a server with IP 12.34.56.78, user "ec2-user" and identity file "MyPrivateKey.key"
- Go to folder "/var/logs"
- Show on console the latest 30 lines of the file "super-app.log"


Task 3 (Automated End-to-End web testing):

Perform a test automation over wikipedia.org search feature and search for “test automation” query, that should lead you to the wikipedia article about test automation. We've already evaluated your test case generation skills on one of the previous tasks, so there's no need to implement more than just the specified user flow.

At this point we don’t care about complexity, we’re just evaluating your proficiency on locating elements and basically your web automation skills. You can use whatever language and automation framework that you desire (we use Js, Java, Cypress and Selenium). Use as many features as you want of the testing framework you choose, use as many patterns you want to, the required reporting is console output, but having a nicer reporting is a plus. The "cleaner" the code, the better.

Please, provide a GitHub repo/cloud folder with the solutions to the tasks and the deliverables.
Good luck!
