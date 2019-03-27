To clone this repository, perform the following steps:
1. Make sure you have git installed on your computer (it is different for Mac OS, Linux, and Windows). You can install git or update it with the link [here](https://git-scm.com/downloads). 

2. Open your terminal (Mac Users it is in Finder -> Applications -> Utilities -> Terminal. Windows users, you should use a terminal emulator from [here](https://gist.github.com/jirutka/99d57c82fa8981f56fb5). It starts downloading when you click it.

3. Configure your github settings. This can be done by editing the `user.name` and `user.email` directly, or editing the entire config file at once. Both ways are given below.

  a. 
  `git config --global user.name 'Github_Name'`
  `git config --global user.email 'Github_email@email.com'`
  
  b. `git config --global --edit` 
    Then, either edit the name and email fields for the `[user]` or add them like this: 
      `[user]
          name = Github_Name
       [user]
          email = Github_email@email.com`
          
4. Move into the folder you want to clone the repository into. `cd` is the command for change director. Please see the Basic Linux commands for a description of how to use `cd`.

5. Type `git clone link_copied_from_github`. The `link_copied_from_github` is the link found from the green drop-down box that says Clone Directory in the repository.

6. Done with the first part of the tutorial!
