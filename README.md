#Mastering Git commands and understanding Git workflows.
Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your computer.
SETUP Configuring user information used across all local repositories <br>
git config --global user.name “[firstname lastname]” set a name that is identifiable for credit when review version history <br>
git config --global user.email “[valid-email]” set an email address that will be associated with each history marker <br>
git config --global color.ui auto set automatic command line coloring for Git for easy reviewing <br>
SETUP & INIT Configuring user information, initializing and cloning repositories <br>
git init initialize an existing directory as a Git repository <br>
git clone [url] retrieve an entire repository from a hosted location via URL <br>
STAGE & SNAPSHOT Working with snapshots and the Git staging area <br>
git status show modified files in working directory, staged for your next commit<br>
git add [file] add a file as it looks now to your next commit (stage) <br>
git reset [file] unstage a file while retaining the changes in working directory <br>
git diff diff of what is changed but not staged <br>
git diff --staged diff of what is staged but not yet committed <br>
git commit -m “[descriptive message]” commit your staged content as a new commit snapshot <br>
BRANCH & MERGE Isolating work in branches, changing context, and integrating changes <br>
git branch list your branches. a * will appear next to the currently active branch <br>
git branch [branch-name] create a new branch at the current commit <br>
git checkout switch to another branch and check it out into your working directory <br>
git merge [branch] merge the specified branch’s history into the current one <br>
git log show all commits in the current branch’s history <br>
INSPECT & COMPARE Examining logs, diffs and object information<br>
git log show the commit history for the currently active branch <br>
git log branchB..branchA show the commits on branchA that are not on branchB <br>
git log --follow [file] show the commits that changed file, even across renames <br>
git diff branchB...branchA show the diff of what is in branchA that is not in branchB <br>
git diff branchB...branchA show the diff of what is in branchA that is not in branchB <br>
SHARE & UPDATE Retrieving updates from another repository and updating local repos <br>
git remote add [alias] [url] add a git URL as an alias <br>
git fetch [alias] fetch down all the branches from that Git remote <br>
git merge [alias]/[branch] merge a remote branch into your current branch to bring it up to date <br>
git push [alias] [branch] Transmit local branch commits to the remote repository branch <br>
git pull fetch and merge any commits from the tracking remote branch <br>


