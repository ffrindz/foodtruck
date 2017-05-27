# Overview

The goal of this is to write a simple commandline program that will print out a list of food trucks, given a source of food truck data from the San Francisco government’s API.

# The Task
## Data
The San Francisco government’s website has a public data source of food trucks. The data can be accessed in a number of forms, including JSON, CSV, and XML. How you access the data is up to you, but you can find some useful information about making an API request to this data source here.

## The Problem
Write a command line program that prints out a list of food trucks that are open at the current date, when the program is being run. So if I run the program on Friday, May 5 at noon, I should see a list of all the food trucks that are open then.

## Additional notes
You should display up to 10 food trucks at a time. Please sort the output alphabetically by name. While we do have unit and integration tests here at Redfin, they are not necessary for this take-home problem. We do expect you to write your code in a clean and testable way so that you would be able to test it in the future!

# Example
```
$ show-open-food-trucks
NAME                  ADDRESS
Mang Hang Catering    1 Thomas More Way
Steve’s Mobile Deli   145 King Street
```
You should use the programming language you feel most comfortable in. Use of any external libraries or packages is permitted and encouraged! This command line utility should run on linux or Mac OSX (if you need an exception to this, let us know).

# Submitting your work
Please email us a zipped folder containing your work, or you may put your solution on GitHub and send us the link. Your submission should include:

1. Your code.
2. A README file that contains instructions on:
  - how to install dependencies.
  - how to build your program.
  - how to run your program, with example commands on how to run it if necessary.

3. A one- or two-paragraph write-up describing, at a high level, what would you do differently if
  - you were asked to build this as a full-scale web application.

# Submission Notes
We recommend you spend roughly two hours on this project.
We don’t expect your write-up to take more than thirty minutes to complete. Therefore, keep your response high-level and not more than two paragraphs. Do spend time polishing and packaging up your submission so it is easy to install, run, and review.

Our goal is to evaluate your submission as anonymously as possible, so please try to remove any identifying information from your code (your IDE may automatically add your name, for example).
