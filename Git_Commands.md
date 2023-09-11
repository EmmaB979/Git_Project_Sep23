# Manual Git Commands

1. `git init`

    Initializing a git project folder

2. `git add <file_name>`

Sending file to staging area

    **How to use it cleverly:**

    use git status before commiting

    `git add <file 1> <file 2>`

    `git commit -m "msg that expresses changes both files have in common"`

3. `git commit -m "meaningful message"`

    How to commit to create my first snapshot

    Meaningful message: Why, how, limitations, effects

    Why writing the message: for future self and collaborators, explain what you did. 

    Without the -m, Git will ask/force you to write a message, can have outline with title      (followed by empty line) and multiple lines with description (not after a "#"). 

        Add i before the last # and delete. (insert)

        After the #, add an enter

        Add a title on the following line

        Add an empty line

        Add description on next lines

        When done, press esc

      On appearing bottom line, type ":wq" to save and quit, commit is then finished

4. `git status`

    Gives uncommitted changes, staged and unstaged changes and untracked files     (completely new files) from all conceptual areas as a report. 

    ALWAYS DO BEFORE ADDING AND/OR COMMITTING

5. `git log`

    `-n <n°>`

    `--abbrev-commit`

    `--help`

    See latest git activities (last n° of commits, abbreviated commit numbers)

6. `git diff`/ `git show`

    Check for differences in commit versions. if you only input one commit number, you     check with the most recent version.

    `git show -n <file name>` 
    shows n latest version of file

7. `.gitignore` is a file containing the names of the files that should not be read in into Git. When sharing on GitHub, people can read the gitignore file, but cannot access the files described within. 

8. `git remote add <Linkname> <ssh>`
   Linkname is the name for your bridge to github, most often this is the name of your project (folder). This sets up the "staging" to github (once it is set up for a session, continue directly to git push)

9. followed by `git push` to upload from local repository to remote repository, github
   
   This pushes whole git to github, excluding files is possible by adding arguments, which is not looked at here. 
