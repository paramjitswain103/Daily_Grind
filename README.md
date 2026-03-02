Created an directory daily-grind and created an repo

git init Configured name and email locally

git config --locally user.name "Paramjit" git config --locally user.email "paramjit@gmail.com" checked the git status and the file was untracked, I did

git add . To add all files

Then I run git status .

now the file is tracked.

git commit -m "feat: initial project setup" Ran git log to find out each commit has its own unique hash

Created new files * menu.txt and style.css

Staged all files with git add .

Before committing I've added changes to style.css

it shows only the style.css has changes.( I have used git lens)

also git diff

git diff --staged shows nothing at first but when I staged that file it shows the differences between the staging area and the last commit

What is difference between staging area and working directory?

Working directory is the folder on your local computer you are working on. Staging area is the overview of our next commit. Created an file apis_keys.json and added It to stagging.

Secret files aren't meant to be in repo or at stagging area.

redo the stagging with git restore --staged

Opened the gitignore with

code .gitignore added the secret file to it committed it Now deleted everything from menu.txt

now messed up everything?

We can restore Everything with

git restore menu.txt Create a new branch

git branch shift to another branch

git checkout or git switch Create plus Checkout in one Command

git checkout -b Created an file named Loyalty.html added some content to it and committed it

Switched to main branch New file? where ?

The changes in another branches doesn't affect the master branch.

don't change the branch yet.

changed some content in index.html and committed it

Now merge the feat-loyalty into main.

Since feat-loyalty and main changed different files it was a simple merge.

changed the shop name to midnight.

switched the branch to rename-test. with checkout -b

Switch back to main and try to merge it.

Got merged!

Changed a chunk if css file.

Stashed it with git stash.

it gave me an clean working tree.

now I can finish the Emergency fixes.

git pop it returns the stashed changes.

git log To see the logs.

to checkout at a specific commit

we an use.

git checkout used

git checkout main to get back to main.
