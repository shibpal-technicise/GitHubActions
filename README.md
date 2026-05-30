How to create a new repository on the command line:

  echo "# GitHubActions" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git branch -M main
  git remote add origin https://github.com/shibpal-technicise/GitHubActions.git
  git push -u origin main
