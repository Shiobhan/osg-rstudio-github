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

3. Choose where on your computer the repository will live.  For me, this is `~/GitHub/`

