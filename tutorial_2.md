# This tutorial utilizes practice_file_t2.txt

You should already know how to: clone a repository on Github. 
In this tutorial, you will learn how to create a branch, change branches, edit text files, and commit changes.

## Part 1: Creating a New Branch
1. Open your terminal. Cd into this Github-Tutorials directory. 

2. Check to make sure your branch has no unsaved changes by typing `git status`. You should get a message that says your branch is up to date. 

3. Check the status of the repository by typing the command: `git pull`. This will check to see if any files have been added to the repository and add them to your repository. It also will add any changes people have made to the files.

4. Create a branch by typing `git branch name_of_branch`. `name_of_branch` can typically be anything, but for this test, we want it to be your Github username to ensure that two people don't try to commit the same branch name.

5. Type `git branch` to see which branch you are on. You should still be on the `master` branch. It indicates the branch you are on by putting an * next to the branch you are on. An example is shown below where you would be on master branch:
  ``` 
      * master
        New_branch_2
        new_branch_1 
  ```


6. Switch to the branch you created by typing the command `git checkout name_of_branch`. 

7. Check that you are on the right branch by typing `git branch`.

8. Push the branch to the origin. This is done to make sure your branch is now saved in the Github repository. To push the branch to the origin, type `git push origin name_of_branch` when you are in the branch `name_of_branch` that you just created.

9. Now that you are on the branch you just made, open the file practice_file_t2.txt. You can use any text editing software you want. Underneath `Hello World!` type what your favorite food is. Then save the document.

10. Now, you have saved your document on your local branch, but your branch and your changes to practice_file_t2.txt don't appear on the Github repository. The next step is to push the file onto the repository.


## Part 2: Adding, Committing, and Pushing Files
To add any changes you make to the Github repository, you have to do three steps: add the document to the next commit. Commit the document(s) that you have changed or created. Then push the commit to the repository.

11. To add documents, type `git add practice_file_t2.txt`. In general, to add documents to the commit, you can do two different things. You can type `git add name_of_document1 name_of_document2 etc`. `etc` can be an entire folder name, or more document names. You can add one or more documents as long as you add spaces in between. If you want to add all documents that you have changed to the commit, type `git add -all`. 

12. After you add the documents to the commit, you want to commit them with a message so that you know what you changed in that commit.
