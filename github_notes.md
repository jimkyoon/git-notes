# What is GitHub?
GitHub is an online repository hosting site. This is where you can store your repositories online! You could also use it to work on projects with other people. GitHub could also be used as a portfolio site!

# Using GitHub
To use GitHub, you want to link your local repository (on your computer) to a GitHub repository! First let's go to the repository you have on your computer. Next we want to add the GitHub repository to yours.
```
cd git_project
git remote add origin https://github.com/<github username>/<github repo name>.git
```
Once it is linked up, you want to push your repository up.
```
git push origin master
```
Origin is the GitHub repository. Master is your local repository.
