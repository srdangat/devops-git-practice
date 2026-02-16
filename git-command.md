# Git Commands


## Setup & Config

### git init
- Initializes a new Git repository.
- **Example**: 
    ```bash
    git init 
    ```
### git config
- Configures Git username or email.
- **Example**:
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "Your Email"
    ```
- View Config Values
- **Example**:
    ```bash
        git config --global --list
    ```

## Basic Workflow

### git add
- Stages files for commit.
- **Example**:
    ```bash
    git add git-commands.md
    ```

### git commit
- Save staged changes with a message explaining what you changed.
- **Example**:
    ```bash
    git commit -m "Add git commands reference"
    ```

## Viewing Changes

### git status
- Lists which files are modified and not yet stage
- **Example**:
    ```bash
    git status
    ```

### git log
- Shows the history of commits in your repository who changed what,when,and why.
- Its also shows Commit hash,Author name & email,Date,Commit message
- **Example**:
    ```bash
    git log
    ```

### git diff 
- Show changes between working directory and staging area
- **Example**:
    ```bash
    git diff
    ```

### git restore
- Restores working directory files.
- **Example**
    ```bash
    git restore git-command.md
    ```

### git diff --staged
- Shows changes between staging area and last commit.
- **Example**:
    ```bash
    git diff --staged
    ```

### git show
- Displays detailed information about a specific commit.
- **Example**:
    ```bash
    git show <commit-hash>
    ```

### git rm --cached
- Removes a file from Git tracking but keeps it in the working directory.
- **Example**:
    ```bash
    git rm --cached file.txt
    ```

### git log --stat
- Shows commit history with file change statistics.
- **Example**:
    ```bash
    git log --stat
    ```

### git log --oneline
- Shows commit history in a compact, one-line-per-commit format.
- **Example**:
    ```bash
    git log --oneline
    ```

### git log --graph
- Displays commit history as a visual graph.
- **Example**:
    ```bash
    git log --graph
    ```

## Branching

### git branch
- Lists all local branches in the repository.
- **Example**:
    ```bash
    git branch
    ```

### git switch <branch> / git checkout <branch>
- Switch to an existing branch.
- **Example**:
    ```bash
    git switch feature-1
    git checkout feature-1
    ```

### git checkout -b
- Create a new branch and switch to it immediately.
- **Example**:
    ```bash
    git checkout -b feature-2
    ```

### git branch -d
- Delete a local branch.
- **Example**:
    ```bash
    git branch -d feature-2
    ```

## Connect Local Repo to GitHub Remote

### git remote add origin
- Connects your local repository to a GitHub remote repository.
- **Example**:
    ```bash
    git remote add origin https://github.com/your-username/devops-git-practice.git
    ```

---

## Push Main Branch

### git push -u origin main
- Pushes the local `main` branch to GitHub and sets upstream tracking.
- **Example**:
    ```bash
    git push -u origin main
    ```

---

## Push feature-1 Branch

### git push -u origin feature-1
- Pushes the local `feature-1` branch to GitHub and sets upstream tracking.
- **Example**:
    ```bash
    git push -u origin feature-1
    ```
