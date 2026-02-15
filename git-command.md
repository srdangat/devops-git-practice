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