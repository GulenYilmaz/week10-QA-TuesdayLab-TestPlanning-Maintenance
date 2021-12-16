# week10-QA-TuesdayLab-TestPlanning-Maintenance


Test Planning, Maintenance, and Layers
You have requirements for a site located here: Employee Manager v1.2 (https://devmountain-qa.github.io/employee-manager/1.2_README.html)

Your task is as follows:

A clear test plan.

For each feature to be tested:

Include the link(s) to the test(s) covering the area.

Brainstorm some potential risks to the quality of the application, and include these, as well as your estimated level of risk.

A set of test cases covering the app’s functionality.

One or more of your tests needs to use equivalence partitioning or boundary value analysis.

If you find any issues, be sure to document them on Trello.

A test summary report detailing your testing thus far, and your opinion of the application.

Attach to your test plan, or as part of the test summary, a state transition diagram with color coding indicating the “status” of that part of the application.

Housekeeping

We’ve been using this project to show examples of how to accomplish the different things we’ve learned, framed as “on the job training” with Brightpaths Labs.

You can use existing work as part of this project.

Know that your work does need to be updated for the most recent version of the app, AND according to the other acceptance criteria.

This is work that needs to be accomplished on your own, though you can still ask your instruction team questions.

All requirements have been covered, you are welcome to review prior skills practices, topics covered, etc.


## Test Summary:

The app  improved over the previous version. 
ID discrepancy has been resolved.
Field length restrictions and content restrictions have been implemented. 
Title field still needs length restriction, see below. Overall quite a bit of work has been done, the app is a lot closer to completion.

1. Entering too long a string in the Name field triggers warnings for the Name field and the Title field at the same time

2. Entering too long a string in the Title field does not trigger any warning. Invalid entries are accepted

Boundary Value Analysis: Phone number


|Invalid|Invalid|Valid|Invalid|
|---|---|---|---|
|0 to 9 digits |9 digits |10 digits |11 digits|

![State Transition Diagram](https://github.com/atchafalaya/Testing_Planning_Maintenance/blob/main/State_Transition_Diagram.png)


