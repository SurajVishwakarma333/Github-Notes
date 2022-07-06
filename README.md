# Github-Notes 

-  To push an project or anything to git, follow these steps :

**Steps 1.** Go to terminal and change working directory to your project root using cd command and enter below commands.
or we can directly right click on inside the folder which we have to commit/push and click on git Bash here.

**Steps 2.** write git init which show git to perform task in this folder .It will generate .git file inside your working folder. 

         git init


**Steps 3.** git status for knowing your folder status means its committed or not if not then it will show files in red color.

        git status


**Steps 4.** git add .   //Adds all the files to local version control.
 
        git add . 


**Steps 5.** here we are commiting
        
        git commit -m "Some Commit Message"


**Steps 6.** git remote add origin repository_url.git 
 
        git remote add origin https://github.com/SurajVishwakarma333/app_name.git


**Steps 7.** git push --set-upstream origin master   //A new branch is created with name master and all the code will be pushed to this branch.
     
        git push --set-upstream origin master


**Steps 8.**  Wait till the code is pushed before doing any other operation in terminal.

After all this, you will get a message similar to Branch 'master' set up to track remote branch master from origin.

# SOME TIPS AND TRICKS WHILE WRITING IN GIT.

![image](https://user-images.githubusercontent.com/101108540/173771871-c9e6f233-3a98-4d8c-875f-b9d9dd84efdb.jpeg)











