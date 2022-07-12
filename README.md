# git_demo

 git init
 git add .
 git commit -m "MSG"
 git remote add origin "GITHUB_REPO_URL"
 git push 
 
 # create branch 
  git branch -M "shubham"
  git checkout shubham
  ** make some changes **
  git add .
  git commit -m "MADE changes on file in beta branch"
  git push origin shubham
  
 # Now we have total of two branches "main" and "beta"
  git checkout main
  git fetch origin shubham
  git merge origin/shubham
  ** solve merge conflicts **
  git push origin main
  

