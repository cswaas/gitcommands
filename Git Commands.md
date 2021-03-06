# Basic Commands

- git init // Initialize Local Git Repository
- git add <file> // Add File(s) To Index
- git status // Check Status Of Working Tree
- git commit // Commit Changes in Index
- git push // Push To Remote Repository
- git pull // Pull Latest From Remote Repository
- git clone // Clone Repository Into A New Directory

# Further Commands

- git --version
- git config --global user.name 'Christian Waas'
- git config --global user.email 'cswaas@gmail'

- git rm --cached <file> // Remove File From Index (Staging Area)
- git add \*.html
- git add .
- git commit //VIM editor opens to write commit comment
- git commit -m 'My commit coment'

- git branch login // Create a branch named 'login'
- git checkout login //Switch to login branch
- git push --set-upstream origin login // To push the current branch and set the remote as upstream
- git checkout master //Switch to master branch
- git merge login // Merge login into master branch
- git remote add origin https://github.com/cswaas/gitcommands.git
- git remote // Display remote repository
- git push -u origin master // Push master to origin repository
- git push // Push further changes to remote repository
- git pull // Pull all changes from remote repository
