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

  62  git status
   63  git add .
   64  git commit -m "Created readme file" -m "for testing porpuse"
   65  git push origin main
   66  git remote add origin https://github.com/LetsCreatProjects/git_test.git
   67  git remote -v
   68  git push -u origin main
   69  git push origin main
   70  git push -u origin main
   71  git push -u origin master
   72  history
   73  git branch
   74  git checkout -b feature-readme-instructions
   75* git bran
   76  git checkout master
   77  history
   78  git status
   79  git add .
   80  git commit -m "update"
   81  git checkout master
   82* git checkout 
   83  git checkout feature-readme-instructions 
   84  git checkout master
   85  git checkout feature-readme-instructions 
   86  history 
   87  git checkout master
   88  git diff feature-readme-instructions 
   89  git status
   90  git push
   91* git diff feature-readme-instructions
   92  git checkout feature-readme-instructions 
   93  git push
   94  git add .
   95  git commit -m "update"
   96  git push
   97  git checkout master
   98  git checkout feature-readme-instructions 
   99  git pull
  100  git checkout feature-readme-instructions 
  101  git checkout master
  102  git branch -d feature-readme-instructions 
  103  history
  104  git checkout - b  quick-test-branch
  105  git checkout quick-test-branch
  106  git checkout -b testB
  107  git status
  108  git diff
  109  git diff master
  110  git commit -am "its addes and msg at the same time. only for modifyed files"
  111  git checkout master
  112  git checkout testB 
  113  git commit -am "header added"
  114  git checkout master 
  115  git commit -am "header added"
  116  git checkout testB
  117  git checkout master 
  118  git commit -am "header added"
  119  git diff
  120  git diff master
  121  git merge master
  122  git status
  123  git commit -am "merge"
  124  git checkout master 
  125  git merge testB
  126  git push
  127  git checkout testB 
  128  git status
  129  git add gitv0/README.md 
  130  git status
  131  git reset
  132  git status
  133  git add gitv0/README.md 
  134  git commit -m "test"
  135  git status
  136  git reset HEAD~1
  137  git status
  138  git diff master
  139  git logo
  140  git log
  141  git commit -am "update last line"
  142  git log
  143  git commit -am "update last line"
  144  git log
  145  git reset acb2ea08f723dcb9edca2feaab0a9a13f26ffb4f
  146  git commit -am "update last line"
  147  git log
  148  git  reset --hard commit acb2ea08f723dcb9edca2feaab0a9a13f26ffb4f
  149  git  reset --hard acb2ea08f723dcb9edca2feaab0a9a13f26ffb4f
  150  git merge master
  151  history