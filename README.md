# gitWorkshop-THS
Introductory Git Version Control Workshop taught at Timberline High School for my     Project-Based Instruction Class.

## Introduction
Hello, students! By now, you should have created your own Github account and registered for the Github Student Developer Pack. Congratulations! You've taken your first steps towards managing your code better and becoming part of the open source community. Now, it's time to learn *how* to better manage your class codebase using Git.

## What is Git?
Git is what is known as version control software ...

## It's coding time!
### Forking a Repository

 1. Navigate to  [my Github repository for this lesson](https://github.com/lbosse/gitWorkshop-THS).
 2. Click the "fork" button in the upper right hand corner of the screen. This will create your own personal copy of the repository in your account, where you can modify it freely without changing the code in my repository. This is often used when using someone else's code as a starting point for your own project or for proposing changes to their project. For more information, check out [this page](https://help.github.com/articles/fork-a-repo/).
 3. You should now see your own copy of this repository on your Github profile page! Click on the repository name to go to it's page.
 4. You'll see a lot of buttons and options on this page! We'll get to those shortly. For now, click on the **"Clone or Download"** button and copy the link it gives you. You can also download it as a .zip file, but we're going to do things the cool way ;)
 
 ### Cloning a Repository to Your Computer
 5. Now that you've got the ".git" link to your repository, open up your terminal and navigate to the directory where you want to place your project folder. Once you're there, type this command into the terminal: `https://github.com/lbosse/gitWorkshop-THS.git`.
 6. You're ready to start working!
 
 ### Committing to a Repository
 7. Open up the file `Greeting.java` with your favorite text editor and add the following method: `public void sayHello() {
 System.out.println("Hello!"); }`
 8. Now, time for the good stuff! When we want to save, or "push" our code to our remote repository (the repository on Github where your code is stored), we first need to add the files we want to save to be tracked by git and "commit" the changes we made to our code. This whole process takes four steps:
a. Run the command `git status` in your project folder. This will show you both changes to "tracked" (files already being watched by git) and "untracked" (new) files. You should see the following message from this command:
b. Add the changes you want to save to your commit by running `git add <file name>`. Do this for both modified and untracked files.
