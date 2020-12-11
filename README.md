# What is Git?

Git is the most commonly used version control system. Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to. Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source. 

So regardless of whether you write code that only you will see, or work as part of a team, Git will be useful for you.

![Image of home page.](https://github.com/moinsoft/Git/blob/master/images/image.png)

# Git Repositories

A Git repository (or repo for short) contains all of the project files and the entire revision history. You’ll take an ordinary folder of files (such as a website’s root folder), and tell Git to make it a repository. This creates a .git subfolder, which contains all of the Git metadata for tracking changes.

On Unix-based operating systems such as macOS, files and folders that start with a period (.) are hidden, so you will not see the .git folder in the macOS Finder unless you show hidden files, but it’s there! You might be able to see it in some code editors.

# Stage & Commit Files

Think of Git as keeping a list of changes to files. So how do we tell Git to record our changes? Each recorded change to a file or set of files is called a commit.

Before we make a commit, we must tell Git what files we want to commit. This is called staging and uses the add command. Why must we do this? Why can’t we just commit the file directly? Let’s say you’re working on a two files, but only one of them is ready to commit. You don’t want to be forced to commit both files, just the one that’s ready. That’s where Git’s add command comes in. We add files to a staging area, and then we commit the files that have been staged.

# Remote Repositories (on GitHub & Bitbucket)

Storing a copy of your Git repo with an online host (such as GitHub or Bitbucket) gives you a centrally located place where you can upload your changes and download changes from others, letting you collaborate more easily with other developers. After you have a remote repository set up, you upload (push) your files and revision history to it. After someone else makes changes to a remote repo, you can download (pull) their changes into your local repo.

![Image of home page.](https://github.com/moinsoft/Git/blob/master/images/image1.png)