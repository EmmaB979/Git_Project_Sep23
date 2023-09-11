# Manual Git Commands

`git init`

Initializing a git project folder

`git add <file_name>`

Sending file to staging area

    **How to use it cleverly:**

    use git status before commiting

    `git add <file 1> <file 2>`

    `git commit -m "msg that expresses changes both files have in common"`

`git commit -m "meaningful message"`

How to commit to create my first snapshot

Meaningful message: Why, how, limitations, effects

Why writing the message: for future self and collaborators, explain what you did. 

Without the -m, Git will ask/force you to write a message, can have outline with title  (followed by empty line) and multiple lines with description (not after a "#"). 

    Add i before the last # and delete. (insert)

    After the #, add an enter

    Add a title on the following line

    Add an empty line

    Add description on next lines

    When done, press esc

    On appearing bottom line, type ":wq" to save and quit, commit is then finished

`git status`

Gives uncommitted changes, staged and unstaged changes and untracked files (completely new files) from all conceptual areas as a report. 

ALWAYS DO BEFORE ADDING AND/OR COMMITTING

`git log`

See latest git activities

`git ignore`
