Dynamic parts of the To Do List User Interface (UI)

1. Add Task to List Section (addTaskToList):
Consists of a text box and a submit button 
The text box is dynamic because a user can input the name of a 
new task in the textbox and submit this using the Add button.
The text in the text box can be modified.

Possible problems: may need to check whether the new task is a duplicate
of an existing task.  We could end up with two tasks with the same name in our database.

2. Count Outstanding Tasks Section
The number of tasks is dynamic because this number will need to be updated
if a user adds a new task in the Add Task to List Section or
deletes or marks a task as done in the Show Outstanding Tasks Section

Possible problems: this count will need to automatically refresh every time
a user adds a new task or deletes/marks a task as done.

3. Show Outstanding Task Section
The table in this section is dynamic because the number of rows will
need to be increased if the user adds new tasks in the Add to Task List Section.
The number of rows in the table will need to be decreased if a user selects the Done or Delete button in the Show Outstanding Tasks section.

Possible problems: we will need to keep making a count of the number of rows in the table as this may vary.  The table will need to update automatically every time a new task is added or a task is delete or marked as one. The table may become very large and there may be problems with displaying the table on the webpage.
We will need some code with the HTML to count the number of rows required in the table
as this is not fixed.
We may need to list the tasks e.g. in alphabetical order, oldest task first etc.

