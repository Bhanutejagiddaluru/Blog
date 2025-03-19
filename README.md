# GitHub Version Control: A Beginner's Guide

## Introduction
Version control is an essential part of software development, allowing teams to track changes, collaborate efficiently, and maintain code history. GitHub, built on Git, is one of the most popular platforms for version control.

In this guide, we will explore the basics of GitHub version control, from setting up a repository to managing branches and pull requests.

---

## 1. Setting Up a GitHub Repository
To start using GitHub for version control, follow these steps:

1. **Create a new repository:**
   - Go to [GitHub](https://github.com/) and log in.
   - Click on `+` (top right corner) → `New repository`.
   - Provide a repository name, description, and choose visibility (public or private).
   - Initialize with a `README.md` (optional).

2. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/repository-name.git
   ```

---

## 2. Basic Git Commands
Once the repository is set up, you can start tracking changes with Git.

### Checking the Git Status
```sh
git status
```
This command shows the current state of your working directory and staged changes.

### Adding Changes to Staging Area
```sh
git add .
```
This stages all modified and new files.

### Committing Changes
```sh
git commit -m "Your commit message"
```
Commits the staged changes with a descriptive message.

### Pushing Changes to GitHub
```sh
git push origin main
```
Uploads local commits to the remote repository.

---

## 3. Working with Branches
Branches allow you to work on new features without affecting the main codebase.

### Creating a New Branch
```sh
git branch feature-branch
```

### Switching to the New Branch
```sh
git checkout feature-branch
```
Alternatively, you can create and switch to a branch in one command:
```sh
git checkout -b feature-branch
```

### Merging a Branch
Once your work is complete, merge the branch into `main`:
```sh
git checkout main
git merge feature-branch
```

---

## 4. Using Pull Requests
Pull requests (PRs) allow collaboration and code review before merging changes.

1. Push your feature branch to GitHub:
   ```sh
   git push origin feature-branch
   ```
2. Go to your repository on GitHub.
3. Click on `Pull Requests` → `New Pull Request`.
4. Select your feature branch and compare it with `main`.
5. Review changes and submit the pull request.

---

## 5. Undoing Changes

### Reverting a Commit
```sh
git revert <commit-hash>
```
Creates a new commit that undoes the previous commit without altering history.

### Resetting to a Previous Commit
```sh
git reset --hard <commit-hash>
```
Moves your branch back to a specific commit (Caution: This deletes changes permanently).

---

## Conclusion
GitHub version control is a powerful tool for developers. By mastering Git commands, branches, and pull requests, you can efficiently manage and collaborate on projects. Start using GitHub today to streamline your development workflow!

### 🚀 Happy Coding! 🚀
