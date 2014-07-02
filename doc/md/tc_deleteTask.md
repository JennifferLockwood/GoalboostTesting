<link rel="stylesheet" type="text/css" href="../testplan.css">

User can delete a task
======================

Steps
-----

* Sign in to Goalboost
* Verify land on task page.
* Verify (Assert?) Add new task button
* Click add new task button
* Enter Title, Description, and Issue Schedule / Status
* Click submit.
* Verify land on Start Timer page
* Click Delete Task link
* Pop up window confirmation
* Verify Cancel and OK buttons
* Click Ok button to confirm action
* Verify land on task page
* Verify task deleted

Expected Results
----------------

* Should see the task page /tasks/<someId>
* Should have the right title, description, status
* Should have a start timer button
* If click Tasks link on top, should see title in the table of tasks.
* Should pop up window confirmation
* Should not see task deleted

Selenium Test Case
-------------------

Not applicable.  Manual test.

[Test Plan](TestPlan.html)
