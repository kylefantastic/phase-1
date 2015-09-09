# 1.5 Tracking changes

#### How does tracking and adding changes make developers' lives easier?
Tracking and adding changes make developers' lives easy because it gives them more control on their projects by allowing to keep track of what happens and what happened. This comes super handy If a developers needs to access or restore a previous version of the project if the current one is broken. For those reasons, it's also a safe way to prevent for loosing data for human computing errors.

#### What is a commit?
A commit is a command `git commit` that is used to record changes to the repository.
After you have staged the content you want to snapshot with the `git add` command, you run `git commit` to actually record the snapshot. Git records your name and email address with every commit you make, then, running `git status` should return `nothing to commit (working directory clean)`

#### What are the best practices for commit messages?
1. Use a short summary (50 characters or less).
2. Use imperative forms of verbs. "Add typeface" and not "Added typeface" or "Adds typeface"
3. Further paragraphs come after blank lines.
4. Bullet points are okay, too but pay attention using the correct markup.
5. Use a hanging indent.

#### What does the HEAD^ argument mean?
HEAD can be understood as the "current branch". When you switch branches with `git checkout`, the HEAD revision changes to point to the tip of the new branch.

#### What are the 3 stages of a git change and how do you move a file from one stage to the other?
**Git have 3 states that files reside in:**

*Comitted:* The files are stored locally on your machine.

*Modified:* The file has been changed but not comitted yet.

*Staged:* The modified file is marked and ready to be comitted.

**It's funny because it also have 3 stages:** ***the working stage***, ***the staging area stage*** **and the** ***.git repository stage.***

For example:

You modify files in a directory. -> ***working directory stage***

From here you can add a snapshot of the file to your staging area -> `git add` -> ***staging area stage***

You do a commit of files as they are in staging area -> `git commit` -> ***.git repository stage***

#### Write a handy cheatsheet of the commands you need to commit your changes?
`git status` -> Show the working tree satus

`git pull` -> - Fetch from and integrate with another repository/branch

`git checkout -b branch-name` Switch branches or restore working tree files

`git add` -> Add file contents to the index (ordered list containing files paths)

`git commit -m "A nice commit message"` -> Record changes to the repository with a message

`git push origin some-branch` -> Update remote refs along with associated objects

`git branch -D branchname` ->  Delete (-D) branches (can also list or create with different options than -D)

#### What is a pull request and how do you create and merge one?
A pull request is an user action done on the github website by hitting the pull request button of a branch. It allows you to compare the contents of two different branches and create a merging request between those two. In a second time, once the request has been created, you can answer the resquest by merging (or refusing to merge) this branch to the target branch. All those merging actions are done in Github.com.
A good practice consists in deleting branchs after they have been merged so you can pull a newer, cleaner, fresher version of the project to work on future improvements.

#### Why are pull requests preferred when working with teams?
Pull requests let you tell others about changes you've made on a repo. The idea is that after a pull request, other members of the team can review the request, discuss it and even commit some changes if needed.