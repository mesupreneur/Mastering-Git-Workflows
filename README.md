#Mastering Git commands and understanding Git workflows.
Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your computer.

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

commit - It is the record of change <br>
git commit -m "Some message" <br>

push - Upload local repo content to remote repo <br>
git push origin main <br>
