# html
Step 1: clone the repository. git clone https://github.com/Zeferu2/html.git
Step 1.1: check status if the displayed message shows red implies modified files but not added. git status
Step 2: add the changes. git add <file1, file2 etc>
Step 2.1: check status if the displayed message shows green implies modified files are added. git status
Step 3: commit the changes. git commit -m "message, example instructions added in the readme.md"
Step 4: create a new branch. git branch <branch name, example feature-readme>
Step 4.1: checkout to a new branch. git checkout feature-readme
Step 5: pull the main branch. git pull origin main
Step 6: push the new branch. git push 
Step 6.1: if the branch is new branch it is expected to be created in github.  git push --set-upstream origin feature-readme
Step 7: create pull request. go to your github repository then click the pull request tab then review the changes then click the create pull request
Step 8: review the pull request and merge the pull request. under the pull request tab you can see the existing pull request then select the intended pull request and review. lastely merge the pull request if there is no conflict.

Step 1: Clone the Repository
git clone https://github.com/Zeferu2/html.git
This command makes a local copy of the specified repository on your computer.

Step 1.1: Check Status
git status
This shows the state of your working directory and staging area. Files shown in red are modified or untracked but not yet staged for a commit.

Step 2: Add the Changes
git add <file1> <file2> ...
This stages the specified files for the next commit. If you want to add all modified files, you can use git add ..
Step 2.1: Check Status Again
git status
Now, the files you added will appear in green, indicating they are staged and ready to be committed.

Step 3: Commit the Changes
git commit -m "message, example instructions added in the readme.md"
This records your changes to the local repository with a descriptive message about what was changed.

Step 4: Create a New Branch
git branch <branch name, example: feature-readme>
Branches allow you to work on different versions of the repository at the same time.
Step 4.1: Checkout to the New Branch
git checkout feature-readme
This switches your working directory to the specified branch, allowing you to work on that version of the project.

Step 5: Pull the Main Branch
git pull origin main
Before pushing your changes, it's a good practice to pull the latest changes from the main branch to ensure your branch is up to date.

Step 6: Push the New Branch
If this is the first push of the new branch, use:
git push --set-upstream origin feature-readme
This command pushes your branch to the remote repository and sets it to track against the remote branch.

Step 7: Create Pull Request
Go to your GitHub repository, click the Pull Request tab, review the changes, and click the "Create Pull Request" button.
A pull request lets you tell others about changes you've pushed to a branch in a repository on GitHub.

Step 8: Review and Merge the Pull Request
Under the Pull Request tab, you can see the existing pull request. Select the intended pull request, review it, and finally, merge the pull request if there is no conflict.
Merging pull requests incorporates the proposed changes from one branch into another (typically main or master).