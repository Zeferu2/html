# html
Step 1: clone the repository. git clone https://github.com/Zeferu2/html.git
Step 1.1: check status if the displayed message shows red implies modified files but not added. git status
Step 2: add the changes. git add <file1, file2 etc>
Step 2.1: check status if the displayed message shows green implies modified files are added. git status
Step 3: commit the changes. git commit -m "message, example instructions added in the readme.md"
Step 4: create a new branch if you are in the main branch or if you finish your task on specific branch. git branch <branch name, example feature-readme> 
Step 4.0: To know your current branch, type git branch.
Step 4.0.1: The branch highlighted in green is your current branch.
Step 4.1: checkout to a new branch. git checkout feature-readme
Step 5: pull the main branch. git pull origin main
Step 6: push the new branch. git push 
Step 6.1: if the branch is new branch it is expected to be created in github.  git push --set-upstream origin feature-readme
Step 7: create pull request. go to your github repository then click the pull request tab then review the changes then click the create pull request
Step 8: review the pull request and merge the pull request. under the pull request tab you can see the existing pull request then select the intended pull request and review. lastely merge the pull request if there is no conflict.