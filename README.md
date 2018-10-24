# git-workshop

## Getting started with git

#### Downloading git for your local machine 

For linux 

```
$ sudo apt-get update
$ sudo apt-get install git
```

For Mac 

```
brew install git
```

For windows, download git from the following source - https://gitforwindows.org/

to check if git is successfully installed, type `git` in your terminal and you should see a bunch of functions appear from it

#### Configuring git

substitute the following with your details of your github account

```
$ git config --global user.name "Emma Paris"
$ git config --global user.email "eparis@atlassian.com"
```

#### Basic functions

1. Creating a local repository - go to the directory which you want to make a git repository 

```
$ cd myproject
$ git init
```

2. Checking tracked and untracked files

```
$ git status
```

3. Adding changes to be tracked

Either a file can be added or all files can be added
```
$ git add <filename>
$ git add .
```

4. Committing a change

Once the changes are added, the changes can be committed, which means you are sealing them, in order to do so

```
$ git commit -m "YOUR COMMIT MESSAGE"
```

5. Pushing the file to your online repository on github.

To do this we set the 

```
git remote add origin <URL OF REPO>
git push origin master
```

6. Getting changes from the remote

```
git pull
```