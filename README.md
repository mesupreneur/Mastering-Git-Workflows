#Mastering Git commands and understanding Git workflows.
Git is the free and open-source distributed version control system that's responsible for everything GitHub-related that happens locally on your computer.

Configuring Git (SetUp) <br>
git config --global user.name "My Name" <br>
git config --global user.email "someone@email.com" <br>

git config --list <br>

Basic Commands <br>
Clone - Cloning a repository on our local Machine <br>
git clone (some link) <br>

Status - displays the state of the code <br>
git status <br>

File Status Life Cycle <br>
Untracked, Unmodified, Modified, Staged <br>

Basic Commands <br>
add - adds new or changed files in your working directory to the Git Staging Area
git add (file name) <br>

To select all <br>
git add . <br>

commit - It is the record of change <br>
git commit -m "Some message" <br>

push - Upload local repo content to remote repo <br>
git push origin main <br>

To create a new git repo <br>
git init <br>
git remote add origin (link) <br>
git remote -v to verify remote <br>
git branch to check branch <br>
git branch -M main (to rename branch) <br>
git push origin main <br>

Branch Commands <br>
git branch (to check branch) <br>
git checkout (branch name) to navigate <br>
git checkout -b (new branch name) <br>
git branch -d (branch name) <br>

Merging Code <br>
git diff (branch name) to compare commits, branches, files, and more <br>

If we are in different branches and want to compare with the main we can write the command <br>
git diff main <br>
Merge Code <br>
git merge (branch name) or git merge main <br>
OR <br>
We can create pull request from Github











