This tutorial utilizes practice_file_t2.txt

You should already know how to: clone a repository on Github. 
In this tutorial, you will learn how to create a branch, change branches, edit text files, and commit changes.

1. Open your terminal. Cd into this Github-Tutorials directory. 

2. Check to make sure your branch has no unsaved changes by typing 'git status'. You should get a message that says your branch is up to date. 

3. Check the status of the repository by typing the command: 'git pull'. This will check to see if any files have been added to the repository and add them to your repository. It also will add any changes people have made to the files.

4. Create a branch by typing 'git branch name_of_branch'. 'name_of_branch' can typically be anything, but for this test, we want it to be your Github username to ensure that two people don't try to commit the same branch name.

5. Type 'git branch' to see which branch you are on. You should still be on the 'master' branch. It indicates the branch you are on by putting an * next to the branch you are on. An example is shown below where you would be on master branch:
  ``` 
      * master
        New_branch_2
        new_branch_1 
  ```



6. Switch to the branch you created by typing the command 'git checkout name_of_branch'. 

7. Check that you are on the right branch by typing 'git branch'

8. Push the branch to the origin. This is done to make sure your branch is now saved in the Github repository. To push the branch to the origin, type `git push origin name_of_branch` when you are in the branch `name_of_branch` that you just created.


9. Now that you are on the branch you just made, open the file practice_file_t2.txt. You can use any text editing software you want. Underneath 'Hello World!' Type what your favorite food is. Then save the document.

10. Now, you have saved your document on your local branch, but if you notice, your branch and your changes to practice_file_t2.txt don't appear on the Github repository.

