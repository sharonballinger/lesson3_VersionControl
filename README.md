# Project Name:  Lesson 3 Version Control

## Course Title:
LIS 2360:  Web Application Development

## Assignment Date:  
July 11, 2017

## Student Name:  
Sharon Ballinger

## Project Description:
#### **Version Control** and **Git**.

## View Project:
https://sharonballinger.github.io/lesson3_VersionControl/

Having multiple people working on a project can cause a huge headache in understanding the status of a project and who has done what. **Git** is about making that headache a thing of the past. **Git** is a version control software and everyone working on the project is able to view and work on the files simultanouesly.

## Lessons Learned in the Assignment:
1. Are you a designer, web developer, writer etc.? If so, you have probably created a print/web ready file that is about to be published/printed when... the dreaded last minute change occurs, it goes off for final approval and there's another change and so on. You file directory might look something like this:

    **graphicdesignPRINT.pdf**
    **graphicdesignPRINT_Final.pdf**
    **graphicdesignPRINT_final2 then 3 then 4 and so on.**
    
    You end up with multiple files that might only have a spelling change but you don't want to get rid of the file just in case you need it because you know when you delete that file the client will want to revert back.
    
    What happens if there are multiple people working on the same files? How do you to keep track of the most current file? This is where we introduce Version Control Systems (VCS); a system that records changes to file(s), who made the change, what they changed, when it changed and compares changes with other users and reverts back to a specific time period if needed.

2. Git is a free and open source distributed version control system designed for small scale projects to extremely large projects with multiple users. Git is used locally so there is not the need to always be connected to the internet, this streamlines projects. Everyone working on a project has a full history of the repository on their system. Git tracks these files by organizing and storing snapshots of content differences with embedded metadata: what changed, who changed what, when it changed and a description of why it changed. Project files can be edited simultaneously by multiple users and merged into one by pushing the files to a centralized repository.

    Each user is able to have independent multiple local branches with an endless number of workflows. When the user is ready to commit the changes they can be 'pushed' to the remote repository. The user doesn't have to push the whole repository just the changes they have made.
    
3. Git has three main states that your files can be in: **committed, modified and staged.**

    **Committed** means the data is stored locally in the Git directory. 
    **Modified** means you have changed the file but it isn't staged. 
    **Staged** means you are making a modified file ready for your next snapshot.

    There are three main sections of a Git workflow: 

    * **the Working Tree/Directory,**
    * **the Staging Area,**
    * **the Git Directory/Repository.**
    
    The Working Tree/Directory is where files are modified. Staged files occurs when you add snapshots to the staging area. In the Git Directory/Repository you permanently commit a snapshot.

