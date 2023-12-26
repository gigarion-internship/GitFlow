# GitFlow
Research about Git Flow and note in Readme.md 
Git Flow

*** Branch

 - When developing, the branch develops independently. When testing is completed, it will be 
 merged into the main branch
 - main/master represents the most stable version.
 - Other branches will develop independently, only then will they be included.
 - Divide the code into small pieces and develop independently so as not to affect the overall code.
- Usually divided as:
   - master
   - develop
     + /feature 
     + /release
     + /hotfix
     + /support
    
*** Commit

 - Record changes in the project.
 - Each commit is usually related to a specific feature, bug fix or improvement.

*** Push
 - Upload commits from local machine to repository.
 - When a feature or bug fix has been tested and completed, developers often push to share it with teammates.
   
*** Pull (pull to computer then merge)
 - Fetch changes from remote repository to local machine.
- To ensure the local machine is always up to date with the latest changes on the repository, especially before starting a new feature or bug fix.
  
*** Merge
 - Merge changes from one branch into another branch.
 - Conflict (editing the same file will cause conflict)
 - Once a feature has been completed and tested on the branch feature, it will be merged into 
 develop. Similarly, when a version is tested and ready, it is merged into the master.
