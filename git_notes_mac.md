# Git Notes (Mac Version)
These are my notes on Git use. Git on Mac OS will be used through the Terminal.

To see notes about the Terminal and how to access it, look at the terminal notes in this folder.

# First step, install Git
Before we start using Git, we need to install it! Go to the Git website, download it, then install it!

[Git](https://git-scm.com/)

Once installed, let's check if it works! In your terminal, type:
```
git
```
You should see a bunch of Git commands that you can look over. Great! It works!

# Set up
First things first, let's set up our user name!
```
git config --global user.name "Jim Yoon"
git config --global user.email jimyoon90@gmail.com
```
To verify:
```
git config --global --list
```
Let's also turn on color.ui so the output of Git can be color coded.
```
git config --global color.ui "auto"
```

# Repository
The repository is where Git or any version control system keeps track of all the changes. Let's create one!

# git init - Starting a repository
To start a repository, go to the folder of a project you are working on. Once inside, type:
```
mkdir git_test
cd git_test
git init
```
Now there is a hidden .git folder inside your project folder. This is where the VCS will keep track.

Now let's create some files and make changes.

# git add . and git commit -m
Let's say we have a file inside our folder, index.html. Say we have a working HTML file and we add in a h1 tag with some content. Now let's add those changes to Git.
```
git add .
```
This will add all the changes to Git. Now let's commit those changes.
```
git commit -m "added h1 to index.html"
```
The -m is a message or memo that is associated with what you committed.

# git log and git diff - Looking at the history
NOTES COMING SOON

# git revert and git reset - Revert to previous history or reset on a commit
NOTES COMING SOON
