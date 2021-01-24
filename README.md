# Understanding PR and Github

## This repository is to teach you about how to start making contributions to the Open-source by making a PR.

![image here](https://github.com/iamvs-2002/Understanding-PR-and-Github/blob/main/GitxGithub.png)

First, let's understand what is **Git** and **Github**.

**Git** is a version control system. In simple words, git is tool that is used to track changes in files (a process called version control).

- Git is used to manage various open-source development projects.
 
**GitHub** allows you to store files in the cloud to access them from any computer and to share them with others.

Now what is a **Pull Request (or a PR)**?

A pull request (referred to as a PR) is a way for you to suggest changes to a repository that are visible and can be easily reviewed.

### Now, how to make a PR?
1. Create a fork( a copy of other users’ files on github.com) of this repository.
- To fork a repository, click the Fork button at the top right in the repository. 
2. Clone that fork to your local computer( copy files from github.com to your computer) and begin to work on CONTRIBUTING.md file in a text editor.
- To clone, click the code button, take a copy of the link provided, then watch as GitHub takes this repository and adds it as a copy to your account.
3. When you are done editing the text file locally on your computer, you save the file and 'git add' and 'git commit' your changes using git.
4. Finally, you 'git push' those changes back up to your fork of this repository.

### Now let's make a contribution to this repo:

- First of all, check if you have Git installed on your computer. 

   * To do so, open the terminal(or the commad prompt), and type the command: 

     *git --version*

    * This shows you the Git version running on your computer.
    * If it shows an error, [Download Git](https://git-scm.com/downloads). 
    * Repeat Step 1 after installing Git.

- Next, fork this repo as described above.
- Then go to terminal and clone the fork to your computer by using the command: 

  *git clone https://github.com/YOUR_USERNAME/Understanding-PR-and-Github.git*

    * It will take some time to clone and also, it might require you to sign in if you are a first time user.

- Now, open the folder in which it has cloned, i.e. Understanding-PR-and-Github, using the command: 

  *cd Understanding-PR-and-Github*

- Then, open the code base using the command: 

  *code .*

**Remember: The code base opens in the text editor you had selected while installing Git.**

- Now, head to the CONTRIBUTING.md file and enter your details in a format described below:

  ```markdown
  Name: [YOUR NAME](Github Link)
  Age: Your age
  About: Short Intro (Optional)
  Country: Your country of residence
  ```

- That's it. Save the file(Ctrl+S).
- Then on the terminal write the following command: 

  *git status*

    * It shows you the changes you have made in the file. It should be in RED Color initially, showing no changes have been made to the file.

- Now, add this changes by using the command: 

  *git add CONTRIBUTING.md*
  
- Now, on the terminal again write the following command: 

  *git status*
  
  * If it shows the file in GREEN Color, you're good to go, else save the file in the text editor and then repeat the process.

- Now, we need to commit these changes and then push them to the Github repository.

  * To commit, write the command: 

      *git commit -m"THE_MESSAGE_YOU_WANT_TO_GIVE"*

  * Now, push the changes using the command: 

      *git push origin main*

**NOTE: Here 'main' means that the changes are being pushed to the main branch.**

- Now, to make a pull request, head to the real repository, i.e., https://github.com/iamvs-2002/Understanding-PR-and-Github and go to [PULL REQUEST](https://github.com/iamvs-2002/Understanding-PR-and-Github/pulls) and click on **New Pull Request** button. Then, select compare across forks and select the forked repo in your profile as the head repository.

**Remember: The base repository stays the same. Then click on create!**

### BOOM! You just made your first PR.

Star this repository(meaning, bookmark this repository) if you find it useful, by clicking on **Star** button on the top right!
