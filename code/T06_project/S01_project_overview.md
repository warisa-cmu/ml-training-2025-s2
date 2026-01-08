# How to Setup Project in Python using `uv`

- `mkdir <project_name>`: Create a new directory for your project.
- `cd <project_name>`: Change into the newly created project directory.
- `uv init`: Initialize a new Python virtual environment in the project directory.
- `uv add <package_name>`: Add a package to the virtual environment.
  - Example: `uv add scikit-learn` to add the scikit-learn library.
- `uv install`: Install all packages listed in the virtual environment's requirements file.

# Installing `git`

- Download and install from https://git-scm.com/
- Set your username and email

```bash
git config --global user.name "firstname lastname";
git config --global user.email "email@example.com"
```

- Check by `git config --list`

# GitHub Repository Setup

- Create a new repository on GitHub.
- `git init`: Initialize a new Git repository in your project directory.
- `git remote add origin <repository_url>`: Link your local repository to the GitHub repository.
- `git add .`: Stage all files for the initial commit.
- `git commit -m "Initial commit"`: Commit the staged files with a message.
- `git push --set-upstream origin master`: Push the initial commit to the main branch of the GitHub repository.

# Subsequent Update

- `git add .`
- `git commit -m "<commit_message>"`: Commit changes with a descriptive message.
- `git push`: Push the committed changes to the GitHub repository.

# Cloning the Repository

- `git clone <repository_url>`: Clone the repository to your local machine.
- `cd <project_name>`: Change into the cloned project directory.
- `uv install`: Install all packages listed in the virtual environment's requirements file.

# Useful Git Commands

- `git status`: Check the status of your working directory and staging area.
- `git log`: View the commit history.
- `git reset --soft HEAD~1`: Undo the last commit but keep changes staged.
- `git reset --hard <commit_hash>`: Reset your working directory to a specific commit.
- `git clean -fd`: Remove untracked files and directories from the working directory.
