# GettingStartedWithGIT
Some basic instructions and resources to get started with GIT

# install & account auth stuff
1. Follow this link[https://help.github.com/articles/about-ssh/] to learn more about SSH.
2. Go here[https://help.github.com/articles/checking-for-existing-ssh-keys/] to check if you have an existing SSH key.
3. Go here[https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/] to generate a SSH Key.
4. Go here[https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/] to add the SSH key to your GitHub account.
5. And finally go here[https://help.github.com/articles/testing-your-ssh-connection/] to test its connection.


# setup
1. start a rmeote by following this https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories
2. create a local repo by navigating to the working directory and running
   ```bash
   git init
   ```
3. add the remote to this local repo
   ```bash
   git remote add <name> <url>
   ```
# Cloning a repo
if you are to start working on existing project just clone the repo
```bash
git clone <url>
```
the repo you cloned from is automatically added as the remote 
# Fetch and Pull
If your workspace has no uncommitted files, and you want to copy the latest changes from a remote repository directly into your working directory, then issue the git pull command.
```bash
git pull
```
If there is some problems while pulling the changes and you want to stop you can use 
```bash
git 
```

it is possible to add flags like --rebase  
check this to learn about them 
https://git-scm.com/docs/git-pull


git pull will bring all the changes from remote to your workspace
```bash
git fetch
git merge
```
git pull is kind of equvalent to both these commands so if you have uncommited changes in your workspace fetch them and merge them after

# Branches
git repo can have many branches that contains different versions of the same project that exists in paralell

creating a new branch
```bash
git checkout -b <new_branch_name> <original_branch> 
```
navigating to different branches
```bash
git checkout <branch_name>
```

# Merge and Rebase
A good video about merge and rebase
https://www.youtube.com/watch?v=zOnwgxiC0OA



