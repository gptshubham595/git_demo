# git_demo

- git init
- git add .
- git commit -m "MSG"
- git remote add origin "GITHUB_REPO_URL"
- git push 
 
 # create branch 
- git branch -M shubham // Only creates branch
- git checkout shubham // creates branch and checks it also
- ** make some changes **
- git add .
- git commit -m "MADE changes on file in beta branch"
- git push origin shubham
  
 # Now we have total of two branches "main" and "shubham"
- git checkout main
- git fetch origin shubham
- git merge origin/shubham
- ** solve merge conflicts **
- git push origin main

# Pull a branch
- git pull origin main

# pull and push 
- git add .
- git commit -m "changes to be added"
- git pull 
- ** solve merge conflicts **
- git push

# remove your changes
- git stash

# download particular github folder
- USING SVN turtle tool
- svn checkout https://github.com/user/trunk/folder -> replaced tree/master with trunk

  

