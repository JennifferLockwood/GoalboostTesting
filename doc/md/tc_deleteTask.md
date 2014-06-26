<link rel="stylesheet" type="text/css" href="../testplan.css">

User can delete a task
======================

Steps
-----

* Sign in to Goalboost
* Verify land on task page.
* Verify (Assert?) task to be deleted
* Verify (Assert?) Work on link for that task
* Click Work on link
* Verify land on Work on page
* Verify (Assert?) Delete Task link
* Click Delete Task link
* Pop up window confirmation
* Verify Cancel and OK buttons
* Click Ok button to confirm action
* Verify land on task page
* Verify task deleted

Expected Results
----------------

* Should see the task page /tasks/<someId>
* Should see task to be deleted
* Should have Work on link
* Should have Delete Task link in Work on page
* Should pop up window confirmation
* Should not see task deleted

Selenium Test Case
-------------------

Not applicable.  Manual test.

[Test Plan](TestPlan.html)
