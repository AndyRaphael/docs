---
weight: 999
title: "Standard Operating Procedure: Setting Up Git for Version Control"
description: ""
icon: "git"
date: "2024-02-05T08:42:31-05:00"
lastmod: "2024-02-05T08:42:31-05:00"
draft: false
toc: true
---

Objective: Establish version control for your software project using Git.

# Pre-requisites:

- Git installed on your machine. (You can download Git from https://git-scm.com/)
- A code editor installed (e.g., Visual Studio Code, Sublime Text).

# Procedure:

1. Initialize a Git Repository:
  * Open your terminal or command prompt.
  * Navigate to the root directory of your project.
  * Run the following command to initialize a Git repository:

```bash
git init
```
2. Create a .gitignore File:
  - Use a code editor to create a file named .gitignore in the project's root.
  - Specify files and directories to be ignored by Git. For example:

```bash
# Ignore node_modules directory
node_modules/

# Ignore log files
*.log

# Ignore editor-specific files
.vscode/
```

3. Add Files to the Staging Area:
  - Use the following command to add files to the staging area before committing:

```bash
git add .
```

 - This command stages all changes. You can replace . with specific file names for selective staging.

4. Commit Changes:
  - Commit the staged changes with a descriptive message using:

```bash
git commit -m "Initial commit"
```

5. Create a Remote Repository:
  - If you don't have a remote repository (e.g., on GitHub), create one.
  - Follow the instructions on the platform to link your local repository to the remote.

6. Push Changes to Remote:
  - Push your committed changes to the remote repository:

``` bash
git push origin master
```

- Replace origin with the remote name if different, and master with your branch name.

Tips:

- Regularly commit and push changes to keep your version control history accurate.
- Utilize branches for feature development and bug fixes.

Conclusion:
Congratulations! You've successfully set up Git for version control in your software project. Remember to follow these steps consistently to track changes and collaborate effectively.

This SOP provides a basic guide for setting up Git. Depending on your project and team requirements, you may need to expand or customize these steps.
