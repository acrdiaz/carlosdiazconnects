# My Awesome Project

## Description
This is a simple project to demonstrate how to create a README file for a GitHub repository.

---

## Quick Start

### 1. Clone the Repository
To get started, clone the repository to your local machine using the following command:

```bash
git clone https://github.com/acrdiaz/carlosdiazconnects.git
```
### 2. Navigate to the Project Directory
Move into the project folder:

```bash
cd carlosdiazconnects
```

---

## Contributing to the Project

### 1. Make Your Changes
Make the necessary changes to the code or add new features.

### 2. Show the current state of your working directory
Show unstaged changes:

```bash
git status
```

### 3. Stage Your Changes
Add your changes to the staging area:

```bash
git add .
```

### 4. Show the current state of your working directory
Show staged changes:

```bash
git status
```

### 5. Commit Your Changes
Commit your changes with a descriptive message:

```bash
git commit -m "update: readme file, add steps to commit changes"
```

### 6. Push your changes
Push your changes to the remote repository, main:

```bash
git push origin main
```

### 7. Display the commit history
To see a detailed list of all the commits made to the main branch, run:

```bash
git log
```

Review if "HEAD" and "origin/main" are on the same commit.

---

## Git Cheatsheet

Here’s a quick reference table for common Git commands:

| Command                          | Description                                      |
|----------------------------------|--------------------------------------------------|
| `git init`                       | Initialize a new Git repository.                |
| `git clone <repository-url>`     | Clone a remote repository to your local machine.|
| `git status`                     | Show the status of your working directory.      |
| `git add <file>`                 | Stage a file for commit.                        |
| `git add .`                      | Stage all changes for commit.                   |
| `git commit -m "Your message"`   | Commit changes with a descriptive message.      |
| `git push origin <branch-name>`  | Push changes to the remote repository.          |
| `git pull origin <branch-name>`  | Pull the latest changes from the remote branch. |
| `git branch`                     | List all branches in the repository.            |
| `git checkout -b <branch-name>`  | Create and switch to a new branch.              |
| `git checkout <branch-name>`     | Switch to an existing branch.                   |
| `git merge <branch-name>`        | Merge a branch into the current branch.         |
| `git log`                        | Show the commit history.                        |
| `git log --oneline`              | Show a simplified, one-line commit history.     |
| `git diff`                       | Show unstaged changes.                          |
| `git reset <file>`               | Unstage a file while keeping changes.           |
| `git reset --hard`               | Discard all local changes and reset to the last commit. |
| `git remote -v`                  | Show the remote repository URLs.                |
| `git fetch`                      | Download changes from the remote repository.    |
| `git rebase <branch>`            | Reapply commits on top of another branch.       |
| `git stash save "stash title"`   | Temporarily stash changes.                      |
| `git stash pop`                  | Reapply stashed changes.                        |
| `git stash apply stash@{0}`      | Reapply stashed changes by stash ID.            |
| `git tag <tag-name>`             | Create a tag for a specific commit.             |

Setup a new Branch

| Command                          | Description                                      |
|----------------------------------|--------------------------------------------------|
| `git checkout -b <branch-name>`  | Create and Switch to the New Branch.             |
| `git branch`                     | Verify the Current Branch.                       |
| `git push origin <branch-name>`  | Push the New Branch to the Remote Repository.    |
| `git push -u origin <branch-name>`| Set Upstream Tracking (Only the first time).    |
| `git branch -r`                  | Verify the Remote Branch.                        |
| `git branch -d <branch-name>`    | Deleting the Branch Locally.                     |
| `git push origin --delete <branch-name>`| Deleting the Branch Remotelly.            |

---

## Additional notes

### 1. list of .gitignore templates
[list of .gitignore templates](https://github.com/github/gitignore/blob/main/VisualStudio.gitignore)

### 2. Readme.md file syntaxis
[Readme.md file syntaxis](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

