
<hr>

__SLIDE NUMBER__: 1

__TYPE__: lesson-title

__TITLE__: Lesson 10 - Manipulating the Filesystem - Part 2



__INSTRUCTOR NOTES__: 



<hr>

__SLIDE NUMBER__: 2

__TYPE__: announcement

__TITLE__: 

__LINK__: [https://docs.google.com/presentation/d/1BIL6LW6m9J29suSvDllMGd1ZtFWMz-kaL2OkMRX-MNE/present?slide=id.g118a4dbf044_1_0](https://docs.google.com/presentation/d/1BIL6LW6m9J29suSvDllMGd1ZtFWMz-kaL2OkMRX-MNE/present?slide=id.g118a4dbf044_1_0)

![](https://github.com/daniel-schroeder-dev/cwhq-slides-test/blob/main/announcement-slide.png)

__INSTRUCTOR NOTES__: 



<hr>

__SLIDE NUMBER__: 3

__TYPE__: recap

__TITLE__: 

__PROJECT URL__: https://projects.pty.cwhq-apps.com/?filename=/i_p13_advanced_python_09/wizardbox/main.py

In the last lesson, you learned how to manipulate the filesystem using Python.

You learned how to create paths and directories from a Python program.

You also learned how to prevent users from hacking our apps using **Path Traversal** attacks.

__INSTRUCTOR NOTES__: - What did we use to manipulate the filesystem with Python?
- How do we create paths? How do we create directories?
- What is a **Path Traversal** attack? How do we defend against it?



<hr>

__SLIDE NUMBER__: 4

__TYPE__: homework-showcase

__TITLE__: 

#### Wizardbox

![](https://github.com/daniel-schroeder-dev/cwhq-slides-test/blob/main/wizardbox.png)


__DESIGN NOTES__: We did one project for both HW assignments so I'm just giving you the link to the second homework since it has all the features.

__PROJECT URL__: [https://projects.pty.cwhq-apps.com/?filename=/i_p13_advanced_python_09/wizardbox/homework-2/main.py](https://projects.pty.cwhq-apps.com/?filename=/i_p13_advanced_python_09/wizardbox/homework-2/main.py)

__INSTRUCTOR NOTES__: The kids don't have sub-folders for each homework assignment, that's just in the instructor folder.

- Display everyone's homework assignment from the last class. Look at the code of at least one student's project to show how everything fits together. If anyone's project is not working, do an in-class code review and let the other students participate in helping fix any issues but don't take too much time debugging; that's what Homework Help and the Forum are for. If anyone did the bonus assignments or something extra, highlight their work here.



<hr>

__SLIDE NUMBER__: 5

__TYPE__: project-glance

__TITLE__: Adding more features to our **Wizardbox** app

__PROJECT URL__: [https://projects.pty.cwhq-apps.com/?filename=/i_p13_advanced_python_10/wizardbox/main.py](https://projects.pty.cwhq-apps.com/?filename=/i_p13_advanced_python_10/wizardbox/main.py)

__DESIGN NOTES__: You can use the same design from lesson 9 here, since it's the same app with a few more features.

![](https://github.com/daniel-schroeder-dev/cwhq-slides-test/blob/main/project-preview.png)

__INSTRUCTOR NOTES__: Today, we'll add features to our **Wizardbox** app that allow users to:
- Create downloadable zip archives of the contents in a folder.
- Remove directories.
- Rename directories.



<hr>

__SLIDE NUMBER__: 6

__TYPE__: map

__TITLE__: 

Today, we'll add more features to our **Wizardbox** app while continuing to learn about ways to manipulate the filesystem from Python.

We'll perform these steps:
1. Allow users to download the contents of a directory
2. Allow users to delete directories
3. Add logic to ensure a directory exists before removing it
4. Allow users to rename a directory
5. Add logic to ensure a directory exists before renaming it

__INSTRUCTOR NOTES__: 



<hr>

__SLIDE NUMBER__: 7

__TYPE__: live

__TITLE__: Explore the starter code

What's been done for you:

- Functions to create/view directories and files.
- A main application loop that allows users to create/view directories and files.
- Stubbed-out conditional statements for creating a zip archive (a downloadable folder), and removing/renaming directories

__INSTRUCTOR NOTES__: 


