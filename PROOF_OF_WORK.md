# PROOF OF WORK

## Git Commit History

The following output shows the commit history of the repository.

```text
commit 25380a5a1c4be348a1193ed705e7c6c939aff776 (HEAD -> main, origin/main)
Merge: 02297fc 49c0489
Author: Abrar Ali <abrarali.se@gmail.com>
Date:   Sun Oct 11 14:31:37 2026 +0500

    Merge pull request #1 from abrarali-se/development

    Development

commit 49c04899b1f04899f8e1a572352e3d9f5d891151 (origin/development, development)
Merge: cf439be f8f2a36
Author: abrarali-se <abrarali-se@gmail.com>
Date:   Sun Oct 11 14:26:55 2026 +0500

    Resolve deployment script merge conflict

commit f8f2a360b75e8577904b980f0a4bef8f71cbca62 (origin/staging, staging)
Author: abrarali-se <abrarali-se@gmail.com>
Date:   Sun Oct 11 14:22:00 2026 +0500

    Update deployment script on staging

commit cf439be042b3593901f8156c3428906e0645467d
Author: abrarali-se <abrarali-se@gmail.com>
Date:   Sun Oct 11 14:17:48 2026 +0500_

    Update deployment script on development

commit 02297fc8eb54d1dc2501b98b87be5d83ded022db
Author: abrarali-se <abrarali-se@gmail.com>
Date:   Sun Oct 11 13:02:19 2026 +0500

    Add deployment script and README


```

## Q1: Difference Between Git and GitHub

Git is a version control system that tracks changes in files and stores project history on a local computer. It allows developers to create commits, manage branches, and compare changes. GitHub is an online platform that hosts Git repositories in the cloud. It helps developers share code, collaborate with others, and manage Pull Requests.

## Q2: Three Stages of Git Architecture

The Working Directory is where files are created, edited, and deleted. The Staging Area contains the changes selected for the next commit using the `git add` command. The Local Repository stores committed changes and maintains the project's version history. These three stages help developers manage and track their work in an organized way.

## Q3: Difference Between git stash pop and git stash apply

Both `git stash pop` and `git stash apply` restore previously stashed changes to the working directory. The `git stash pop` command restores the changes and removes the stash entry if the operation succeeds. The `git stash apply` command restores the changes but keeps the stash entry in the stash list. The `apply` command is useful when the same saved changes may be needed again.

## Q4: Difference Between git fetch and git pull

The `git fetch` command downloads new information and commits from a remote repository without integrating them into the current branch. It allows developers to check remote updates before applying them. The `git pull` command fetches remote changes and integrates them into the current branch, usually through a merge or rebase depending on the configuration. Fetch is useful for checking updates first, while pull is useful for updating the current branch.