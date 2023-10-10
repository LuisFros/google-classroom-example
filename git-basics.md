# Table of Contents

1. [Git Commands](#git)
2. [Basic Command Line Commands for Mac and Windows](#basic-command-line-commands-for-mac-and-windows)


# Git

Git is a version control system that helps you manage and track changes in your code or files. Here are some common Git commands in order of usage:

### `git pull`

- **Purpose:** Pulls the latest changes from a remote repository (like GitHub or GitLab) to your local repository.

- **Usage:** After making sure you are in the right directory within your project, you can use `git pull` to fetch and merge the latest changes from the remote repository into your local branch.

### `git add`

- **Purpose:** Stages changes for commit. It tells Git which files or changes you want to include in the next commit.

- **Usage:** After modifying files in your project, you use `git add` followed by the file name or a wildcard (`git add .` for all changes) to stage the changes for the next commit.

### `git commit`

- **Purpose:** Records the staged changes in a new commit with a descriptive message. Commits are like checkpoints in your project's history.

- **Usage:** Once you've staged your changes with `git add`, you use `git commit -m"Your commit message"` to create a commit with a meaningful message describing the changes you made.

- **Possible issue:** If you get a message saying that you need to set and author/user name to git. You need to run the following commands
  - `git config --global user.email "yourgithubemail@email.com"`
  - `git config --global user.name "yourGithubUsername"`
 

### `git push`

- **Purpose:** Pushes your local commits to a remote repository, making your changes available to others or storing them in a central repository.

- **Usage:** After committing your changes locally, you use `git push` to upload your commits to a remote repository, such as GitHub. This shares your work and keeps it synchronized with others collaborating on the project.


- **Possible issue:** If you get a message saying that you need need to login or are not allowed to push:
  1. Go to `https://cli.github.com/` and download the client
  2. Open a new terminal and run the command `gh auth login`
  3. Follow the steps on the terminal by pressing the enter key (the first option is enough). There will be 4 options and pressing enter for all should be enough


# Basic Command Line Commands for Mac and Windows

Let's assume you have a folder called "IDA2023" on your computer.

### Print Working Directory

- **Mac:** Shows your current directory. For example, if you are inside the "IDA2023" folder, running `pwd` will display its path.
- **Windows:** you can use the `cd` command

### Change Directory

- **Mac/Windows:** Switch to a different directory. For instance, to enter the "IDA2023" folder, you would run `cd IDA2023` or `cd ../` to move up the directory 

### List Files and Directories

- **Mac:** Lists files and folders in the current directory. If you run `ls` inside "IDA2023," it will display the contents of that folder.

- **Windows:** Use `dir` to do the same. Running `dir` inside "IDA2023" will show the contents of the folder.

### More resources:
- https://linuxjourney.com/lesson/the-shell
