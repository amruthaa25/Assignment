# Assignment
 
1. a. Initialize a local git repository in a new directory and add a text file named "sample.txt" to the
repository. Commit the file with a meaningful message.

To initialize a local git repository in a new directory:

1.	Open Terminal.
2.	Navigate to the directory where you want to create the new repository.
3.	Run the following commands in git bash

SOLUTION:
git init  //initialize the git
git status
notepad sample.txt
git add sample.txt
git commit -m "My assignment"
git log 
git remote add origin "https://github.com/amruthaa25/Assignment.git"
git push origin master

b. Create a new branch called "feature-branch" and switch to that branch. Add some content to
"sample.txt" and commit the changes.

 SOLUTION:
git branch feature_branch
git checkout feature_branch
notepad sample.txt  //commit the changes in the notepad
git add .
git commit -m "added sample.txt, assignment"
git push origin feature_branch

c. Merge the "feature-branch" back into the main branch (usually "master" or "main"). Resolve any
conflicts if they occur.

SOLUTION:
git checkout master 
git merge feature_branch
git push origin master 



