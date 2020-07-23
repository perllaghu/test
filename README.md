# What is NBGrader?

NBGrader is a tool for managing homework, or assignments.

Normally, this is in the form of questions to test whether students can write `code` to solve problems.

Nbgrader views the world in two ways: `Instructors` can set & mark assignments; `students` complete assignments & submit for marking.

In Noteable, `Instructors` are `students` with more options.

## Top level view of assignments

At the very top level, the life-cycle of a notebooks is _create_, _release_, _fetch_, _submit_, _grade_, _feedback_:

* Instructors _create<_ and _release_
* Students _fetch_ and _submit_
* Instructors _grade_ and _feedback_

## nbgrader for students

When you start a notebook, you have three _tabs_ top-left - the `Assignments` one is where you interact with assignments released to your course

![top tabs](three_tabs.png)

This page has three areas: `Released assignments`, `Downloaed assignment`, and `Submitted assignments`.

### `Released assignments`

New assignments will be listed here

![Released assignments](released_assignments.png)

Clicking on `[ Fetch ]` will download it for you to work on.

### `Downloaded assignments`

Assignments you have downloaded are listed here.

![Downloaded assignments](downloaded_assignments.png)

Notice the assignments are listed in alphabetical order, and that each assignment has a right-facing arrow.

If you click on the name of the assignment (or arrow-head) the assignment will _open_ to show you the notebook(s) for you to work on.

Clicking on the notebook name will open the notebook.

#### Working on assignments

When in a notebook, you will only be able to edit certain cells - the ones where you're providing answers (either code, or free-form text)

Remember to **save** your notebook before closing it - if you don't, then you'll submit the last auto-saved version.... which is probably missing important work.

#### Submitting assignments

Having worked on an assignment, and saved it, you can return to the `assignments` tab and check your work by clicking on the `[ validate ]` button.

You may edit, save, validate; edit, save, validate as often as you need until you are ready to submit your work.

Click on the `[ Submit ]` button to return your work to the Instructor.

**Note**, if you realise you have an error (or just want to change the way you do something), you can edit, save, validate... and re-submit - the instructor will be given your last submitted notebook when then collect notebooks for marking.

### `Submitted assignments`

This is where all your submissions are listed

![Submitted assignments](submitted_assignments.png)

There are two things of note here:

1. All your submissions are grouped under their assignments, and timestamped - the instructor _will_ see the timestamp for the submission they're marking.
1. There may be feedback available for submissions, and this is where you fetch it.

