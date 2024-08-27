
# README

This repository includes commands for managing submodules and committing changes in Git. Below is a guide on how to use the provided commands.

## Git Commands

### 1. Create an Empty Commit
You can create an empty commit, which is useful for triggering builds or workflows without changing any files.

```bash
git commit --allow-empty -m "Build"
```

### 2. Update Submodules
To update a submodule in the repository, use the following command. This example assumes you're using an SSH key located at `~/Falinwa/Cluedoo17`.

```bash
GIT_SSH_COMMAND="ssh -i ~/Falinwa/Cluedoo17" git submodule update --remote
```

### 3. Commit Changes
To commit all changes in your repository with a specific commit message, use the following:

```bash
git add -A && git commit -m "[UPD] Update submodule CLuedoo17 02August 1112"
```

### 4. Push Changes to a Specific Branch
To push your committed changes to a specified branch, replace `testxxxxxx` with the name of the target branch.

```bash
git push origin testxxxxxx
```
