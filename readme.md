# Hello World!

A place for first-time installation notes, GitHub practice, and guides for other topics.

## First-time setup on Windows

1. Install [GitHub Desktop](https://desktop.github.com/) and sign in to your GitHub account.
2. In GitHub Desktop, choose **File > Clone repository** and select `Queond/hello-world`. If it is already cloned, select it under **Current repository**.
3. Choose a local folder you can find again. Open that folder in your editor.
4. Read this file (`readme.md`). This repository contains documentation; there is no application to install or run.

For GitHub's full setup instructions, see [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop).

## Make your first change

1. Select this repository and fetch updates. Pull if GitHub Desktop offers incoming changes.
2. Create a branch with a descriptive name, such as `docs/setup-notes`.
3. Edit a document, then review the changes in GitHub Desktop.
4. Enter a short commit summary and commit to your branch.
5. Publish the branch or push your commits, then create a pull request targeting `master`.
6. After the pull request is reviewed and merged, switch to `master` and pull the updates.

## Repository details

- GitHub repository: [Queond/hello-world](https://github.com/Queond/hello-world)
- Default branch: `master`
- `origin`: your copy on GitHub, where this repository's changes belong.
- `upstream`: the original source, if configured. Check the destination before pushing.
- `readme.md`: this guide.
- `README`: the original Hello World greeting.

## Installation notes for other tools

Add a guide under `docs/` for each tool or topic. Each guide should include:

- What the tool does and which operating systems it supports.
- Prerequisites and an official download link.
- Installation steps and how to check that installation worked.
- Common errors and their fixes.
- Update and uninstall instructions.
- The version and date you verified.

Link new guides from the topic list below when their files exist.

## Topics to develop

- Software installation and configuration.
- Git branches, commits, and pull requests.
- Troubleshooting and maintenance.
- Repository backups and restoration.
- Small practice projects and learning notes.

## Backups and restoration

A repository clone stores Git history that was fetched into it. Keep a separate backup for uncommitted files and other local content. A Git clone does not by itself preserve GitHub issues, pull requests, settings, or uploaded release files.

To recover a repository, first determine whether the backup is a normal working clone, a bare repository, or a Git bundle. Restore it into a separate folder and inspect its branches and history before publishing. Push only to the intended destination; mirror pushes can replace or delete remote references.

GitHub wikis use separate Git repositories and require separate backups. Initialize the destination wiki on GitHub before restoring its pages.

## Troubleshooting

- **Repository missing:** check the signed-in account and your repository access.
- **Push rejected:** fetch updates and resolve conflicts before trying again.
- **Changes missing on GitHub:** confirm the branch and whether the commits were pushed.
- **Permission denied locally:** check access to the repository folder.
- **Unsure what changed:** inspect the diff and commit history before continuing.
