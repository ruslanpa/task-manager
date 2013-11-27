task-manager
============

Task Manager

Functional requirements
-----------------------

1. I want to be able to create/update/delete projects
2. I want to be able to add tasks to my project
3. I want to be able to update/delete tasks
4. I want to be able to prioritise tasks into a project
5. I want to be able to choose deadline for my task
6. I want to be able to mark a task as 'done'

Technical requirements
----------------------

1. It should be WEB application
2. For the client side must be used: HTML, CSS (any libs as Twitter Bootstrap, Blueprint ...), JavaScript (any libs as jQuery, Prototype ...)
3. For server side any language as Ruby, PHP, Python, JavaScript, C#, Java ...
4. It should have client side and server side validation.
5. It should look like on screens (see attached file ‘rg_test_task_grid.png’).

Additional functionality
------------------------

1. It should work like one page WEB application and should use AJAX technology, load and submit data without reloading a page.
2. It should have user authentication solution and a user should only have access to their own projects and tasks.
3. It should have automated tests for all functionality.

SQL TASK:
---------
Given tables:

1. tasks (id, name, status, project_id)
2. projects (id, name)
3. get all statuses, not repeating, alphabetically ordered
4. get the count of all tasks in each project, order by tasks count descending
5. get the count of all tasks in each project, order by projects names
6. get the tasks for all projects having the name beginning with “N” letter
7. get the list of all projects containing the ‘a’ letter in the middle of the name, and show the tasks count near each 8. project. Mention that there can exist projects without tasks and tasks with project_id=NULL
9. get the list of tasks with duplicate names. Order alphabetically
10. get the list of tasks having several exact matches of both name and status, from the project ‘Garage’. Order by matches count
11. get the list of project names having more than 10 tasks in status ‘completed’. Order by project_id
