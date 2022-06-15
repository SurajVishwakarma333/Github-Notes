# Github-Notes 

**To push an project or anything to git, follow these steps :**

**Steps 1.**Go to terminal and change working directory to your project root using cd command and enter below commands.

> Steps 2. 

         git init


> Steps 3. 
git status  //This would output you list of files in red color.

        git status


> Steps 4.
 git add .   //Adds all the files to local version control.
 
        git add . 


> Steps 5. 
        
        git commit -m "Some Commit Message"


> Steps 6. 
git remote add origin repository_url.git 
 
        git remote add origin https://github.com/SurajVishwakarma333/app_name.git


> Steps 7. 
git push --set-upstream origin master   //A new branch is created with name master and all the code will be pushed to this branch.
     
        git push --set-upstream origin master


> Steps 8.
 Wait till the code is pushed before doing any other operation in terminal.
After all this, you will get a message similar to Branch 'master' set up to track remote branch master from origin.
