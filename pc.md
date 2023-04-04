## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

Answers:

1. Git is a version control system that tracks changes in computer files. Reference: https://docs.github.com/en/get-started/quickstart/set-up-git

2. The difference between Git and GitHub is that Git is a system that is ran locally directly on the users pc while GitHub is a platform like YouTube to where you can upload and store different types of code remotely and not on the users pc. Reference: https://www.simplilearn.com/tutorials/git-tutorial/git-vs-github#:~:text=While%20Git%20is%20a%20tool,copies%20of%20a%20Git%20repository.

3. Developers create a branch because developers need a way to differentiate the code that they work on, make, or edit from the Master branch. Developers also create branches because it provides a history of the code that has been wrote for that specific project. Branches also serve as a saving point. Lets say someone writes some code that ends up breaking whatever they are working on. They can revert to a previous branch before they wrote that bad code. Reference: https://www.atlassian.com/agile/software-development/branching#:~:text=Branching%20allows%20teams%20of%20developers,other%20developers%20on%20the%20team.

4. Pull requests show other developers the changes that you have made to branches in the repository. Reference: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests

5. The git checkout command is the command that you use when you want to switch between different branches. Reference: https://www.atlassian.com/git/tutorials/using-branches/git-checkout#:~:text=Git%20checkout%20works%20hand%2Din,to%20switch%20to%20that%20branch.

6. The difference between git fetch, git merge, and git pull is that a git fetch fetches updates but doesnt merge. But a git pull fetches and also merges. When you git fetch it checks for changes but doesnt merge them, your master stays the same. When you git pull you check for changes and then you merge them. A git merge merges your changes to the main branch. Reference:https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch#:~:text=not%20merge%20them.-,git%20pull%20does%20a%20git%20fetch,hood%20and%20then%20a%20merge%20.&text=git%20fetch%20is%20similar%20to,a%20remote%20and%20instantly%20merges.

7. A merge conflict happens when two different branches make changes to the same line or when someone edits a file and another person deletes that file. Reference: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line

8. In order to resolve a merge conflict you have to open up the file that has the merge conflicts and rewrite the line that has the errors and then git add and git commit your changes. Reference: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line
