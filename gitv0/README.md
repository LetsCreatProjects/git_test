testB branch header some more change
header of the master



git 

   73  git branch
   74  git checkout -b feature-readme-instructions
   75* git bran
   76  git checkout master

<!-- to delete the branch -->
   git branch -d {branchName} 

<!-- to create a branch -->
   git checkout - b  quick-test-branch

This is a new branck named test

some texts


osboxes@osboxes:~/repositories/git_test$ git add gitv0/README.md 
osboxes@osboxes:~/repositories/git_test$ git status
On branch testB
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   gitv0/README.md

osboxes@osboxes:~/repositories/git_test$ git reset
Unstaged changes after reset:
M       gitv0/README.md
osboxes@osboxes:~/repositories/git_test$ git status
On branch testB
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   gitv0/README.md

no changes added to commit (use "git add" and/or "git commit -a")