# Contributing

## Welcome to the project

Contributions are welcomed and encouraged.
Before you contribute, please read our guidelines carefully.

### Steps to contributing (GUI)

1. Create a GitHub account.
2. Fork this repository to your GitHub account.
3. [Check for issues](https://github.com/KillYourFM/contribute-foss/issues) whether your contribution hasn't been proposed already.
4. (*Optional*) Create a new branch with a name based on what you want to add.
5. Edit your fork. Make sure to document your changes in the commit message.
6. Create a [pull request](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork).
7. (*Optional*) If you created a new branch and the pull request is merged, feel free to [delete your branch](https://github.blog/2013-01-09-create-and-delete-branches/).

### Steps to contributing (CLI)

1. Create a GitHub account.
2. Install `git` via your package manager.
3. (*Optional*) [Add SSH keys](https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account) to your account.
4. (*Optional*) [Add GPG keys](https://help.github.com/en/articles/generating-a-new-gpg-key) to your account.
5. Fork this repository to your GitHub account.
6. [Clone](https://help.github.com/en/articles/cloning-a-repository) **your** fork with `git clone` *your-github-repo*.
7. (*Optional*) Create a new branch with `git checkout -b` *new-feature-or-change*.
8. Make your changes. Make sure to document your changes in the commit message.
9. Push the changes to your repository with these commands:

    ```bash
    git add .
    git commit -am "YOUR COMMIT MESSAGE HERE"
    (Optional) git push --set-upstream origin <branch_name>
    git push origin
    ```

10. Create a [pull request](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork).
11. (*Optional*) If you created a new branch and the pull request is merged, feel free to [delete your branch](https://github.blog/2013-01-09-create-and-delete-branches/) or run these commands:

    ```bash
    git checkout master
    git push --delete origin <branch_name>
    git branch -d <branch_name>
    ```

### How to keep your fork in sync with the upstream repository

Here is a short tutorial from Michael Tunnel <a href="http://www.youtube.com/watch?v=C5WxrnRVmuY"><img src="http://i.ytimg.com/vi/C5WxrnRVmuY/maxresdefault.jpg" width="560" height="315" /></a>

#### Steps to syncing with upstream repository (CLI)

1. Add a new remote for upstream repository with this command:

    ```bash
    git remote add upstream https://github.com/KillYourFM/contribute-foss.git
    ```

2. Sync with upstream repository with these commands:

    ```bash
    git pull origin master
    git pull upstream master
    git push origin master
    ```
