# How to push Eclipse project to Github

### Create repository and add project files: 
 
1. Right click on project-> Team-> Share Project->  
2. Select Git and click on Next,  
3. Click checkbox "use or create repository in parent folder of project",  
4. Select your project from below box,  
4. Click on "create Repository" below and click Finish.  

### Write commit:
  
1. Right click on project-> Team-> Commit->  
2. Write commit message (e.g. first commit),  
3. Select checkbox below of your project directories and files you want to push
     (don't select git files which name contains 'ignore' words e.g. gitignore) and
    then click Commit.  

### Push to GitHub:  

1. Right click on project-> Team-> Remote-> Push->  
2. Enter Git Repository Link in the URL field,  
3. Enter Username and Password and click Next.  
4. From 'source ref:' dropdown select "master [branch]",  
    from 'destination ref:' select "master [branch]" and
    from 'Remote ref to delete' select "master [branch]".  
5. Click on "Add All Branches Spec" and "Add All Tags Spec",  
6. Click "Force Update All Specs" and then click Finish.  
7. You will see a message like "Pushed to -your repository link-" and then click OK.

### Go to your GitHub Repository and check the project has been pushed.