## Otago Study Group: integrating RStudio and GitHub

Goals of this session:

1. Link your RStudio application with your GitHub account.

2. Fork an existing repository on GitHub.

3. Clone the repository to your computer as an RStudio project.

4. Make edits within RStudio, then commit and push back to GitHub.

5. Create a brand new GitHub repository, and repeat 3 and 4.

<BR>

#### 1. Link your RStudio application with your GitHub account

The document "Happy Git and GitHub for the useR":

http://happygitwithr.com

provides detailed advice on how (and why) to integrate GitHub with RStudio.

In particular, [Section 3.1](http://happygitwithr.com/workshops.html#pre-workshop-set-up) of that document provides instructions on linking your GitHub account with your local RStudio installation.

<BR>

#### 2. Fork an existing repository on GitHub.

To get started, let's find a really simple repository ("repo") on GitHub, and copy 
("fork") it to our own GitHub account so that we can make modifications to it.

#### 3. Clone the repository to your computer as an RStudio project.

Now that we have a GitHib reposiory that we would like to modify, we can use the 
Git functionality with RStudio to do this (we talk about this being a "local" copy of the repository, since it is copied, or "cloned" to our laptop or desktop computer), and set the local repo up as a RStudio project.

1. Within RStudio, choose "New Project" from the "File" menu, and then select "Version Control"
from the popup that appears.  

2. Click "Git", and then paste the repository URL (the one associated YOUR account, not my original) into the "Repository URL:" field.  HINT: hitting tab will populate the "Project Directory Name" with the original name of the repository (but you can also call it anything you want).  

3. Choose where on your computer the repository will live (for me, this is the `~/GitHub/` directory), and then click "Create Project". If you click the "Open in new session" checkbox, then a new instance of RStudio will be opened with the new project loaded (otherwise the project opens in the current RStudio instance).

4. You've done it! The GitHub repo that you forked via the website has now been copied to you  computer. Click on the "Files" tab (bottom right panel of RStudio interface) to prove it - you should see a list of all the files in the top directory of the repo (just like on the GitHub website).

#### 4. Make edits within RStudio, then commit and push back to GitHub.

Now it gets cool - let's make some edits.  The repository you cloned only contains a few files - the main one is `README.md`, which describes the repo itself (this is what is displayed when you visit the repo's page on GitHub).

1. Click on the `README.md` file in the "Files" tab on open it in the RStudio editor.

2. Make some edits!  Just add some text and then save it.

3. Go to the panel above, and find the "Git" tab.  Clicking on the should reveal a list of files that have been altered since we cloned the repository.  Click to "stage" the altered files (i.e., get them rewady for syncing with GitHub), and then click the "Commit"" button above the file names - this will open the "Review Changes" window.

4. Write a Commit message!  The Review window allows you to click on each altered file and see the additions (green) and deletions (red) relative to the previous version.  Write a brief message explaining the changes in the "Commit message" box, and then click commit.

5. To "push" the changesup to GitHub, click the "Push" button in the top-right of the Review window.  Woohoo!  You have just sent the changes back to GitHub.  

6. Let's have a look - go to the repository web page on the GitHub site, and refresh the browser.  You should see your commit message next to the names of the altered files, and the message below the file list should now contain your edits from the `README.md` file.




