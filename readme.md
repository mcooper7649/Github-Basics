## Git, GitHub, and Version Control 
---

Why is version control useful?

-Version Control allows us to roll back to a previous version. This is useful when you release a update and its irrepairable otherwise.


Git is a Command Line application, although they do have a standalone client.



## Git Basics Challenge
---

Touch chapter1.txt 
Open chapter1.txt lets you open individual files.
Code . Lets you open all your local directory in the Vscode application.
Commit Chapter 1
Create Chapter 2 and 3
Commit the new Chapters
Now intentionally mess you text up of chapter 3
Git Diff chapter3
Checkout latest version of chapter3


### Steps needed to use git to create a working directory
----


1. git init   // lets you initialize a repo in the working directory.
2. git status   // lets you see if you have any files currently tracked or in staging
3. git add filename // lets you individually add files to staging from that directory
4. git add * or .  // lets you add all files in that directory to staging
5. git commit -m "your message of what changed" // you can commit using this command. this commits to your local repository.
 - The -m flag is important for the whole version control to be useful
 - Side Note When making commits use the present tense not the past.
6. git log // This will show you the hash info of your current commit and the commit message
7. git diff // lets you look at a file and compare changes from now and last commit to local repo
8. git checkout // lets you roll back the current file to last version that was commited.
9. git remote add origin (address from github) // this adds the remote repo location
10. git branch -M main  // New command for setting the branch to Main
11. git push // Pushs commit from local repo to remote



### GitHub | Remote Repository
---

1. Create a repo on github to get the generated address // Example: https://github.com/mcooper7649/Github-Basics.git
2. Copy repo information
3. We can leave out the first few steps listed because we already did a git init, git add, git commit. We just need to add the remote repo. 
```
git remote add origin https://github.com/mcooper7649/Github-Basics.git
git branch -M main
git push -u origin main

```
4. Once we sucessfully push we can refresh our repo page and see our files.


