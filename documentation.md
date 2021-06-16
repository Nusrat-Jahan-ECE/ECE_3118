# **Git**

> ***Git** is a distributed version control tool that can manage a programmer's source code history.*

 It is designed to handle minor to major projects with high speed and efficiency. It is developed to co-ordinate the work among the developers. The version control allows us to track and work together with our team members at the same workspace.

Git is foundation of many services like **GitHub** and **GitLab**, but we can use Git without using any other Git services. Git can be used privately and publicly.

![Git and Github](https://res.cloudinary.com/practicaldev/image/fetch/s--8CA40E5L--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/721lt9kj92i3ov2cthfc.png)

# **GitHub**
> ***GitHub** is a Git repository hosting service. It is a web-based service.*

GitHub is an online service to store code and push from the computer running the Git tool. GitHub focused on centralized source code hosting.

# **Git Commands:**

Git supports many command-line tools and graphical user interfaces. The Git command line is the only place where we can run all the Git commands.

Here is a list of basic Git commands that are used daily:

# ***1. Git Configuration:***


## **i. Git Config:**

The Git config command is the first and necessary command used on the Git command line. This command sets the author name and email address to be used with your commits. Git config is also used in other scenarios. 

**Syntax**
```
git config --global user.name "Nusrat-Jahan-ECE"  
git config --global user.email "1710011@student.ruet.ac.bd"
````

## **ii. To check git version:**

We can check your current version of Git by running the following command in Git Bash, terminal (Linux, macOS) or command prompt (Windows).

**Syntax:**
```
git --version
````



# ***2. Starting a Project:***

## **i. Git Initialization:**

To create a blank repository, open command line on your desired directory and run the init command as follows:
```
git init
````

## **ii. Git Clone:**

![Git clone](https://www.w3docs.com/uploads/media/default/0001/03/3f26b30cc1dbda3424ceef3ab4977149906a0c58.png)


This command is used to make a copy of a repository from an existing URL. If I want a local copy of my repository from GitHub, this command allows creating a local copy of that repository on your local directory from the repository URL.

**Syntax:**
```
git clone <URL> 
````


# ***3. Local Changes:***


## **i. Git Add:**

This command is used to add one or more files to staging (Index) area.

**Syntax:**

**a. To add one file:**
```
git add <Filename>  
````
**b. To add more than one file:**
```
git add*
````
**c. To add all files:**
```
git add -A
````
## **ii. Git Commit:**

This command changes the head. It records or snapshots the file permanently in the version history with a message.

![Git add vs Git commit](https://res.cloudinary.com/practicaldev/image/fetch/s--Si7ksd-d--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://cdn-images-1.medium.com/max/800/1%2AdiRLm1S5hkVoh5qeArND0Q.png)


**Syntax:**

```
git commit -m " Commit Message"  
````

# ***4. Track Changes:***

## **i. Git Status:**

The status command is used to display the state of the working directory and the staging area. It also lists the files that you've changed and those you still need to add or commit.

**Syntax:**
```
git status
````

# ***5. Commit History:***

## **i. Git Log:**

This command is used to check the commit history.

![Git log](https://www.blog.nakulrajput.com/wp-content/uploads/2018/10/Git-Status.jpg)

**Syntax:**
```
git log
````

# ***6. Branching:***


## **i. Git Branch:**

![Git branch](https://res.cloudinary.com/practicaldev/image/fetch/s--Jc-acrrl--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/69payngupg75rqgabwdg.png)


Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously. We can use the git branch command for creating, listing and deleting branches.

**Syntax:**

**a. Creating a new branch:**
```
git branch <branch-name> 
````
This command will create a branch locally. To push the new branch into the remote repository, you need to use the following command:

```
git push -u <remote> <branch-name>
```
**b. Viewing branches:**
```
git branch or git branch --list
```

**c. Deleting a branch:**
```
git branch -d <branch-name>
```

## **ii. Git Checkout:**

![Git checkout](https://static.javatpoint.com/tutorial/git/images/git-checkout.png)


This is also one of the most used Git commands. To work in a branch, first we need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits.

**Syntax:**
```
git checkout <name-of-your-branch>
````