# Git Tutorial

# GitHub Tutorial: Essential Git Commands

## 1. Staging Changes

Staging is the process of preparing files for commit. It allows you to choose which changes you want to include in your next commit.

```bash
# Stage a specific file
git add filename.txt

# Stage all changes
git add .

# View staged changes
git status
```

## 2. Committing Changes

Committing creates a snapshot of your staged changes, saving them to your local repository.

```bash
# Commit with a message
git commit -m "Your commit message here"

# Commit all changes (including unstaged) with a message
git commit -am "Your commit message here"
```

## 3. Pushing Changes

Pushing uploads your local commits to a remote repository, like GitHub.

```bash
# Push to the default remote branch
git push

# Push to a specific branch
git push origin branch-name
```

## 4. Pulling Changes

Pulling fetches changes from a remote repository and merges them into your current branch.

```bash
# Pull from the default remote branch
git pull

# Pull from a specific branch
git pull origin branch-name
```

## 5. Merging Branches

Merging combines changes from different branches.

```bash
# Switch to the branch you want to merge into
git checkout main

# Merge another branch into your current branch
git merge feature-branch

# If there are conflicts, resolve them and then:
git add .
git commit -m "Merge feature-branch into main"
```

## 6. Handling Merge Conflicts

Merge conflicts occur when Git can't automatically resolve differences between branches.

1. Open the conflicting file(s) in your text editor.
2. Look for the conflict markers (<<<<<<<, =======, >>>>>>>).
3. Manually edit the file to resolve the conflict.
4. Remove the conflict markers.
5. Stage the resolved files and commit the changes.

## 7. Best Practices

- Commit often with meaningful commit messages.
- Pull changes before starting new work to avoid conflicts.
- Use branches for new features or bug fixes.
- Review changes before committing and pushing.
- Keep your local repository up to date with the remote.

Remember, practice makes perfect. The more you use Git, the more comfortable you'll become with these commands and concepts.