sfTODOList
==========
Functional Specification
--

Juan José Bernal Rodríguez

Last Updated: March, 18th 2016

Overview
--

A TODO list consists of several **tasks** ordered in a linear manner from top to bottom.

Each **task** has a *title*, a *description*, *created date*, *finished date* and *deadline*, being *title* the only mandatory input, and the rest optional.

Users of the app are able to **view** their TODO lists, **add** tasks, **modify** and **tick** them off as complete. **Deleting** and **reordering** tasks are a plus.

>### Technical note
To be able to hide tasks instead of deleting them, there is a boolean **visible** field that is set to *false* when the task has been ticked off. There is also implicit an **id** unique for each task.
In order to reorder tasks there is a numeric **order** field that holds the current order of the task in the TODO list.

### Viewing tasks
Just after login, the user can see his/her TODO list. By default only unfinished tasks are visible.
If there are no tasks in the TODO list yet, the user is invited to enter a new one.

validation

Screen design
--
