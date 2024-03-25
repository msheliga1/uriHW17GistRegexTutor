# Regular Expression Gist Tutorial
uri bootcamp HW 17 - Regular Expression Gist Tutorial - MJS 3.24.24   
Michael Sheliga - This repo is for the University of Richmond (URI) coding bootcamp.  
Starter Code from: https://github.com/coding-boot-camp/bug-free-goggles

## Link to Repo, Screenshot(s) and/or Video(s)  
Link to GitHub Repo: https://github.com/msheliga1/uriHW17GistRegexTutor      
<!-- Link to Video on Google Drive: https://drive.google.com/file/d/15i1SyN7UNKhFnAYD3HnOhx8d3yip52xh/view  -->  
<!---  Link to deployed github.io site. https://msheliga1.github.io/uriHW9NodeReadmeGen --->  
<!-- Link to logo.svg: https://github.com/msheliga1/uriHW10OOPLogoGenerator/blob/main/examples/logo.svg  --->  
<!-- Link to Video on GitHub [Link](./examples/hw10LogoGenSheliga.webm)   Note that this video may be too large to play in GitHub, so you will need to download and play from your computer. WindowsMediaPlayer worked for me.  -->

[Link to Acceptance Criteria ](#acceptance-criteria)   

## Project Goals     
Use node, SQL and sequalize to create a back-end for an e-commerce site.  

========================================================   
## Technical Project Details    
========================================================    
## Github:   
    Create Repo (github, repositories => New)   
        - Dont Make this a shared repo.  
    Clone the entire starter repo  
        -- Create a new, TOTALLY blank repo in GitHub  (no readme. It will screw things very badly!)
        -- Clone the starter repo (under the hwXX directory) to your local machine
        -- Rename the starter repo if you wish.
        -- Set the remote path: git remote add <ori> <HTTPS path to remove>   
            -- Be 100% sure NOT to use the SSH link. Use the HTTPS lank!  
        -- Push the local repo to gitHub: git push ori main   
    OR ... Copy directories and sample files from prior project (or create from scratch).  
        -- No starter code. No need for copying one file at a time via command line.  
        -- Alternate: Go to Demo (root) folder, download zip, moving to local repo, unzip - likely fastest method.     
        -- Took a long time to figure out how to clone an entire repo!
    OR ... create HTML, Node, Develop, CSS and javascript, etc. from scratch, and copy sample files ... worked well.
        Branches (Optional for single programmer projects)  
        - Could do work in branches. (new branch inside gitHub)    
        - All branch names will begin with the initials of the main person working on the branch.  
        - Must update local repo after adding a branch  
        - Switch to branch: From cmd line git switch <branchname>   
        - Once changes committed, git push origin <branchname>  
            - for pushing to remote test branch: git push origin local_branch:remote_branch  
        - Issue a pull request in gitHub.  
        - Click "Pull Requests" in top menu bar (3rd from left).  
        - Click "review Required" in small font below pull request name.  
        - You may approve your own request.  

    Create a nice long READ.md file!!  (Modify prior projects.)   
    NPM: Do "npm init --y" BEFORE "npm install" to avoide ENOENT err.
         Do "npm install inquirer@8.2.4" (with old version) to avoid require error.
         Do "npm install mySQL2" 
    Commit and push files back to gitHub/branch. (For multi-programming: Issue pull request, approve, merge).  
    Deploy code (Settings...CodeAndAnimation->Pages on left, GitHub Pages->Branch->main, save)  
        - Deployed code name always msheliga1/github.io/RepoName !!  
    Make Sure it Works   
    Insert Screencastify (Chrome) Video and/or Screenshot X2 of deployment into readme file. 
  
## Tools and Technologies Used   
    Github - Branches not needed, but could use.  
        - GitIgnore to keep NPM libraries out of gitHub repo.  
    NPM - Node Package Manager  (package.json)
        fs - fileSystem    
        inquirer - Used for prompts (text, list, checkboxes, editor, etc.)   
        dotenv - for secure db password
        mysql2 - dont forget the 2
        express - ORM
        sequelize - avoid rewriting common SQL queries
    mySQL - install is from the DEVIL!
    SQL - Standard Query Language 
    Insomnia - Used for testing routes
    Agile - Try to assign a little work at a time.   

## Acceptance Criteria   
-----------------------   
Tutorial with buttons and description using GIST.   

Regex Tutorial
open the tutorial => see 
    a descriptive title and introductory paragraph explaining the purpose of the tutorial, 
    a summary describing the regex featured in the tutorial, 
    a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
click on the links in the table of contents => taken to the corresponding sections of the tutorial
Each section of the tutorial: Has a detailed explanation of what a specific component of the regex does
End of the tutorial: has a section about the author and a link to the author’s GitHub profile

