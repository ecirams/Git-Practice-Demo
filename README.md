![Cloud Interest Group](/ciglogo.png)

### GIT Practice Demo Project - Welcome to CIG Members

# 1. Set up git bash environment remote desktop for the first time

```
Step 1.1 - Config user      `git config --global user.name '<name>'`
Step 1.2 - Config email-id  `git config --globa user.email abc.gmail.com`
Step 1.3 - Check the changes    `git config --list`
```

# 2. Create a new repository at remote desktop using Git bash & push to GitHub

New repository at remote desktop can be done using IDE like VS Code. Below steps are to create using the Git bash commands.

```
Step 2.1  - Create a directory to store a repository `mkdir <dir name>`
Step 2.2  - Initialize the git repository    `git init`
Step 2.3  - Add/Create files to the directory
Step 2.3a - Check the status                `git status`
Step 2.4  - Add files to stage area          `git add . (or filename)`
Step 2.4a - Check the status                `git status`
Step 2.5  - Commit changes to repo           `git commit -m "message"`
Step 2.5a - Check the status                `git status`
Step 2.6  - Check the log to see commit id   `git log`
Step ...  - Repeat Step 2.5 & 2.6 to make all necessary changes in the branch
Step 2.7  - Create a repository at Github with the same name
Step 2.8  - Copy origin URL (example https://github.com/name)
Step 2.9  - Connect to the repo GitHub `git remote add origin https://github.com/name`
Step 2.10 - Check the remote repository  `git remove -v`
Step 2.11 - Push files to GitHub    `git push -origin master`
Step 2.12 - Check at GitHus with files
```

# 3. Clone this (Git-Practice-Demo) repository to remote desktop

This is a repository with a single file for enabling students to fork and make changes to the file.

```
Step 3.1 - **Fork**  the _repository_ to your GIT account
Step 3.1a - Clone the repository to your Azure DevOps Repos  (Optional)
Step 3.2 - Clone the same to your local machine
Step 3.3 - Create a branch with a name "feature1"  `git branch <feature_name>`
Step 3.4 - Edit index.html  - Refer the instructions in line  39 and 40
Step 3.5 - Merge the branch with Main
Step 3.6 - Raise a Pull-REquest
```

# 4. Create a repository at Azure repos

```
Step 4.1  - Create an account at Azure DevOps, Create an organization and project
Step 4.2  - Fork project (if it is others GitHub account) to your GitHub Account
Step 4.3  - Get the URL to clone the repo.
Step 4.4  - At Aure Repos - Import repository - Provide the link copied above & enter
Step 4.5  - Verify that copying of all file &  directories from the origin
Step 4.6  - Create a branch, make changes, merge and initiate a pull request.
```
