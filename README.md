**Git** is the key tool we use to allow multiple people to work on the same code base.  **Git** takes care of merging everyone's contributions smoothly.  Hence, learning how to use Git is critical to contributing to open source.


**Exercise 1: Initial setup**

    First things first, you should start by clone this project to your local Repo. 
    There're things that you take care of:
  * GitConfig: Make sure that this local Repo is using your GitHub account and know the difference between the local Configuration for each     Repo and Global Configuration and which one replaces the other
  * For this Repo, you will be using your own GitHub account so you need to configure your account accordingly. 
  
  **Exercise 2: Your First Commit**

  * Now We should make our new commit, for this exercise it will be adding new text file with your name.
      for example: ataha.txt. Your commit should be descriptive for easier changes tracking.
  * After committing your changes you should push it to the master branch.
  
  **Exercise 3: Edit your Commit**

      We have already created a text file with our names but we need to 
      add another java file to the same commit. 
      Take Care that you need to add it to the same commit not different commit.
      It will be yourname.java
      
  **Exercise 4: Add new files and make it untrackable**
   
      Add a new file and make it only locally accessible means it shouldn't be tracked
      
 * Add new text yourname_myuntracked_File.txt
 * Take a screenshot with gitstatus command
 * Add the screenshot to your local Repo
 * Commit only the screenshot and push it to the repo
 
    
  **Exercise 5: Edit old file**
   
      Edit yourname.txt file and add hello yourname inisde it
      Note: Take care of handling unstaged files when you have commit to push
      
 * Edit yourname.txt file
 * Add new file called yourname2.txt
 * Commit only the modified file not the new one which will be in this case yourname.txt and push it to the repo
    
    
  **Exercise 6: Linear Changes**
      
      Should we use Pull or Fetch and rebase in order to get the latest changes 
      on the master branch and have linear changes??
* Do your Search
* Add your Findings and what you recommend in a new File called yourname_myfindings.txt
* Commit this file and push it to the repo
* You should have a file called yourname2.txt that hasn't been staged
* Remove this file ( Check git reset and how to use it)
    
    
   
   
     
    
