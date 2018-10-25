1. Create repository and add project files:  
    a. Right click on project-> Team-> Share Project->  
    b. Select Git and click on Next,  
    c. Click checkbox "use or create repository in parent folder of project",  
    d. Select your project from below box,  
    e. Click on "create Repository" below and click Finish.  

2. Write commit:  
    a. Right click on project-> Team-> Commit->  
    b. Write commit message (e.g. first commit),  
    c. Select checkbox below of your project directories and files you want to push
         (don't select git files which name contains 'ignore' words e.g. gitignore) and
        then click Commit.  

3. Push to GitHub:  
    a. Right click on project-> Team-> Remote-> Push->  
    b. Enter Git Repository Link in the URL field,  
    c. Enter Username and Password and click Next.  
    d. From 'source ref:' dropdown select "master [branch]",  
        from 'destination ref:' select "master [branch]" and
        from 'Remote ref to delete' select "master [branch]".  
    e. Click on "Add All Branches Spec" and "Add All Tags Spec",  
    f. Click "Force Update All Specs" and then click Finish.  
    g. You will see a message like "Pushed to -your repository link-" and then click OK.

4. Go to your GitHub Repository and check the project has been pushed.