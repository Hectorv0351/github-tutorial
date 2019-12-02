# GitHub Tutorial

_by Hector Vargas_

---
## Git vs. GitHub
To start off i'm going to explain the difference between Git and Github  

**Git** is a _**distrubted version control**_ and what it git does mainly is when your coding you could save your changes and they'll be saved but it past changes and saves won't be deleted in a way but stored, another thing about it is that if you want to go back to a past change you could.
one thing about Git is...
- Git doesn't Require github to work

**GitHub** is a _**collabortive version control**_ platform which uses git for it's version control and other people could also collab on the same thing as youif you wanted too, so in short github is website that requires git to work and by using git you can keep track of changes or versions but with github it's easier and with collab it helps with that too using version control with all people within the collab
Things from github are...
- Github requires git to work
- Github makes it easier to use version control
- Github makes it so you could collab with others

---
## Initial Setup
- Now that you have the basic idea of Git and Github we are going to have to make ourselves a github account which is a simple proccess if you don't have a account just go to github and press sign up then just make your account.  
- Now we move on to something called IDE which means **integrated Development Software** which has to be used with github as github is not a IDE itself so to setup a IDE first you will need a IDE so that you'll be able to edit and work on your code so one that we'll be using is **[CS50](https://ide.cs50.io/)** now to set it up you'll have to follow the instructions on this [github Page](https://github.com/hstatsep/ide50).  
- Now that you're finished with that we have to talk about SSH keys which is a important part as when linking a remote which will be shown later you'll come across 2 options when linking or copying a repository which is the SSH key and the HTTP Key and when choosing the link the SSH is the best as you just need the SSH key and you'll be able to just continue and save while the HTTP key you'll need to put you're Username and password everytime.


---
## Repository Setup
*Before we set up a repository im going to explain what it is*
- a repository is different from a directory/file as when making a directory it's just normal folder with nothing and what makes a repository a repository is that a repository has hidden filse in it which makes it able to use git commands.
- Now that you know what a repository is and your IDE is set up and ready to use github we move onto making yourself a repository maybe your first one too.
- We want to initialize git in the folder which will become the Repository so to do that you must go inside the folder which you want to become the repository and use the command "git init" which then transforms the git init
begin we'll have to go into top right where the + icon is and click on it then click on new repository.  
![alt text](https://i.gyazo.com/b7e979aa7aafcfdf7b44cdee30490e87.png)  


---
## Workflow & Commands  

Now that you have created a _repo_ it's time to move onto on how commands work and how you're going to use them. Starting with a basic commands

- `git add`
    - to use `git add` simply do `git add file` and it'll add the file you chose onto the "stage".
    - think of `git add` like you're adding someone to a photo getting them ready.
- `git status`
    - just type in `git status` and you'll be able to see the status of your files and you'll see what as been **modified** and/or **deleted**.
    - `git status` can be seen as just checking on the **stage** and what has been done since the last "photo"
- `git commit`
    - `git commit` is nearly the last step but is still improtant as it saves and takes a "snapshot of the code"
    - the commit command is just the snap in the photo as the photographer takes the picture
- `git push`
    - 
    - 


---
## Rolling Back Changes