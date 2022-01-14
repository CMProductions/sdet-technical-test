# SDET Technical Test
Welcome to the Software Development Engineer in Test technical test!

**IMPORTANT: Bonus tasks are not mandatory but their successful delivery gives you additional points.**

## Task 1 - Exploratory testing & bug reporting
Your first task is to find a bug on any website on the internet and create a bug report out of it. The more severe the bug the better, the more famous the site the better. No worries, there’s a ton of bugs out there waiting for you!

## Task 2 - Software analysis
You have 10 minutes to test a release of Whatsapp before it hits production, what would you test? You have the following devices to test: Android, iOS and Desktop.

## Task 3 - API testing & test case generation
Here you'll find a REST API:
https://developers.giphy.com/docs/api/endpoint#search

This is a sample call to retrieve a list of GIFs:
http://api.giphy.com/v1/gifs/search?q=funny+dog&api_key=dc6zaTOxFJmzC

Your third task is to extensively test that API endpoint. You can use the provided *api_key*: it’s a public key for testing out that API. Please, read the documentation before starting.

Provide a list of test cases (minimum 10, maximum 20), covering both functional and non-functional, listing the actual parameters used to execute your test cases (you can use a test matrix). Try to cover as many features and edge cases as possible: this endpoint allows a lot of parameter combinations.

### Bonus - Automated API testing
You can automate task #3 if you want to. You can use whatever technology and framework you like (we use Js + Supertest, Java + RestAssured and also Postman).

## Task 4 - SQL
Given the tables:

`users`
```
user_id username
1       John Doe
2       Jane Don
3       Alice Jones
4       Lisa Romero
```

`training_details`
```
user_training_id user_id training_id training_date
1                1       1           "2021-07-02"
2                2       1           "2021-07-03"
3                3       2           "2021-07-02"
4                4       2           "2021-07-04"
5                2       2           "2021-07-03"
6                1       1           "2021-07-02"
7                3       2           "2021-07-04"
8                4       3           "2021-07-03"
9                1       4           "2021-07-03"
10               3       1           "2021-07-02"
11               4       2           "2021-07-04"
12               3       2           "2021-07-02"
13               1       1           "2021-07-02"
14               4       3           "2021-07-03"
```
Write a query to get the list of users who took a training lesson more than once in the same day, grouped by user and training lesson, each ordered from the most recent lesson date to oldest date.

## Task 5 - Linux
How would you:
- SSH into a server with IP 12.34.56.78, user "ec2-user" and identity file "MyPrivateKey.key"
- Go to folder "/var/logs"
- Show on console the latest 30 lines of the file "super-app.log"

## Task 6 - Automated end-to-end web testing
With a test automation framework of your choice, test [Wikipedia](https://wikipedia.org)'s search feature by searching for "Voyager 1". We've already evaluated your test case generation skills on a previous task, so there's no need to implement more than just the specified user flow.

You can use whatever language you desire (we use Js + Mocha + Cypress/Selenium). Use as many features as you want of the testing framework, use as many patterns you want to. The required reporting is console output, but having a nicer reporting is a plus. The cleaner the code, the better.

We’ll evaluate your programming skills and web automation skills.

### Bonus - Automated end-to-end mobile testing
You are requested to do the same thing as of task #6 but on the mobile app of Wikipedia. Android or iOS, either is fine (you can test both if you like). As for task #6, framework's choice is free (we use Js + Mocha + WebdriverIO with Appium).

## Deliverable
Please, provide a GitHub repo/cloud folder with the solutions to the tasks and instructions on how to run the tests.

You can provide a Makefile with targets for easier executions and a Dockerfile if you wish.

Good luck!
