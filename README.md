# Mathlib

push local repo to Github

- following https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github

- create completely empty repo on Github Mathlib

…or create a new repository on the command line
echo "# Mathlib" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/johnraz99/Mathlib.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin https://github.com/johnraz99/Mathlib.git
git branch -M master
git push -u origin master