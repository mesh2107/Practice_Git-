Practice_Git-
A demo repository containing my Git practice code, experiments, and notes while learning Git and GitHub commands.

git is a version control systems(vcs). vcs are used to track changes in our project code.

github- is website , that uses git. 

#SETTING UP GIT

windows (git bash )  or mac (terminal) write the given below command to check whether there is git on your device.

  git --version 
if this doesnot show any version on your device then download git from web and also visual studio code.



#AFTER INSTALLING FIRST THING YOU DO IS "Configuring git"
When you first install Git, it needs to know who you are — like your name and email. This information is added to every commit you make.

So, configuring Git just means setting up your identity and preferences.

>>Global Configuration:
Think of this as default settings for your entire computer.

It applies to all Git projects you create or clone on your system.

You usually do this once after installing Git.

The following commands are used for global configuration 
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"


Local Configuration:
Think of this as settings for one specific project/repo only.

It applies only to that particular folder/project.

It overrides the global config inside that repo.

The following commands are used for global configuration
  git config user.name "Another Name"
  git config user.email "another@example.com"


How to Check Your Config?
To see global config:
  git config --global --list

To see local config (in current repo):
  git config --list

