# Ungraded Assignment 3

## Install Shell Analysis Tool for Bash Scripting
Install `shellcheck` on at least three machines in the lab.

```bash
sudo snap install shellcheck
```

---

## Practice Git from the Command Line
1. Create a directory called `first-cli-git-project` anywhere in your home folder.
2. Create an empty file called `file.txt` in `first-cli-git-project`.
3. Create an empty file called `.gitignore` in `first-cli-git-project`.
4. Convert `first-cli-git-project` into a Git repo.
5. Add the existing files to the new repo, then create your initial commit.
6. Open Firefox and log into your GitHub account.
7. Create a new repo called `first-cli-git-project`.
8. Go back to The Terminal, and, from inside the `first-cli-git-project` folder, enter the following, replacing `<YOUR_GITHUB_HANDLE>` with your GitHub username/handle.

    ```bash
    git remote add origin git@github.com:<YOUR_GITHUB_HANDLE>/first-cli-git-project.git
    git push -u origin master
    ```

9. Add the following contents to `.gitignore`:

```
# Ignore everything that ends in a tilde
*~

# Ignore everything that ends with a “._”
._*

# Ignore trash
.Trash-*
```

10. Commit the change, then push.

---
