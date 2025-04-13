# ai-startup-website
Third DevOps mini project

## INTRODCUTION
The purpose of the project, is to simulate real-world team collaboration workflows using Git and GitHub, specifically focusing on pull requests and merging changes while resolving conflicts and synchronizing branches as necessary.

## PROJECT DETAILS
1. ### Install Git.

I visited https://git-scm.com/ to download Git. I installed in on my local machine. a screenshot of Git cli enviroment is shown below, with the git version displayed. The Git version is 2.49.0.windows.1

A screenshot of the Git CLI is below

![](/img/1.Install-git.png)

2. ### Create GitHub account.

I visited https://github.com and created a Github account

![](/img/2.GitHub-account.png)

3. ### Create a repository.

I created a GitHub repository named "ai-startup-website", and also added a readme.md file.

![](/img/3.ai-startup-website.png)

4. ### Clone the repository

I cloned the new repository into a git-project directory in my local machine.

I copied the repository url https://github.com/Crescentius00/ai-startup-website

In Git, I ran the clone command, created an index.html file, ran the status, add, commit and push commands. The commit message is "My first commit".

![](/img/4.Git-clone.png)

5. ### Tom's work.

I simulated Tom's work. I created a new branch called "Update-navigation", made changes to the index.html file by updating the navigation bar. Then I ran the status, add, commit and push commands. The commit message is "updated navigation bar".

![](/img/5.Toms-work.png)

6. ### Jerry's work.

I simulated Jery's work. I pulled the "Update-navigation branch from github and created a new branch called "Add-contact-info. I made changes to the index.html file by adding contact information. Then I ran the status, add, commit and push commands. The commit message is "added contact information".

![](/img/6.Jerrys-work.png)

7. ### Reviewing And Merging Tom's work

To review and merge Tom's work to the main branch, I took the following steps:
1. I navigated to the GitHub repository https://github.com/Crescentius00/ai-startup-website.
2. I switched to the Update-navigation branch
3. I reviewed Tom's changes
4. Clicked on Create New Pull Request
5. Finally I merged the branch after ensuring there are no conflits.

The screenshots below shows how I created pull request and merged Tom's work.

![](/img/7.Toms-pull-request.png)

![](/img/8.Merge-toms-request.png)

8. ### Reviewing And Merging Jerry's work

To merge Jerry's work, Jerry has to use the git pull command to pull up the latest version of the project, use the git checkout command to switch to the Add-contact info branch. He then used git push origin add-contact-info to push to GitHub.

I then took similar steps like I did for Tom:
1. I navigated to the GitHub repository https://github.com/Crescentius00/ai-startup-website.
2. I switched to the Add-contact-info branch
3. I reviewed Jerry's changes and ensured there are no conflict
4. Clicked on Create New Pull Request
5. Finally I merged the branch after ensuring there are no conflits.

The screenshots below shows how I created pull request and merged Jerry's work.

![](/img/9.Jerrys-pull-request.png)

![](/img/10.Merge-jerrys-request.png)