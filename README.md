# Sabio-tutorial
Learning how to navigate GitHub and Git Bash 

Note:

  -use branches to keep changes local to one division
  
  -once changes are done, merge with master
  
  -BOOM! newMerge deleted, but all changes were brought back to master thru a verified pull request

Git Bash notes:
	Step 1) Open a new directory with 'cd'
	Step 2) 'git clone <insert URL>' the GitHub repository
	Step 3) use 'git remote -v' and then 'git remote add upstream <insert URL>'
	Step 4) make a new branch with 'git checkout -b <insert branch name>'
	Step 5) Make whatever changes necessary; check the repo with 'git status'
	Step 6) push changes with 'git add -A' and 'git push origin HEAD'