---
layout: ../../layouts/post.astro
title: Git Basics
description: Git Basics-> Essential Commands and Demos
dateFormatted: May 18th, 2024
---

Git Basics: Essential Commands and Demos

Today, I’ll dive into the fundamental Git commands every developer should know. Git is a powerful version control system that helps you manage and track changes in your codebase. Whether you’re a beginner or just need a refresher, these commands will get you started.

Git offers a range of commands to handle everything from basic version control to complex branching strategies. Let's explore some of the essential commands with examples.

<!-- Replace with an appropriate image showing Git command usage -->

Key Commands

1. git init:
Initialize a new Git repository in your project directory.

Demo

```bash
$ git init
Initialized empty Git repository in /path/to/your/project/.git/
```

2. git clone:
Clone an existing repository from a remote server.

Demo

```bash
sh
$ git clone https://github.com/example/repo.git
Cloning into 'repo'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 10 (delta 1), reused 10 (delta 1), pack-reused 0
Receiving objects: 100% (10/10), 1.23 MiB | 1.23 MiB/s, done.
Resolving deltas: 100% (1/1), done.
```

3. git add:
Add files to the staging area to prepare for a commit.

Demo
```bash
sh
$ git add filename.txt
```

4. git commit:
Commit the staged changes to the repository with a message.

Demo
```bash
sh
$ git commit -m "Add new feature"
[main 1a2b3c4] Add new feature
 1 file changed, 1 insertion(+)
```

5. git push:
Push your commits to a remote repository.

Demo
```bash
sh
$ git push origin main
Counting objects: 5, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 487 bytes | 487.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0)
To https://github.com/example/repo.git
   1a2b3c4..5d6e7f8  main -> main
```

6. git pull:
Fetch and merge changes from the remote repository to your local branch.

Demo
```bash
sh
$ git pull origin main
From https://github.com/example/repo
 * branch            main     -> FETCH_HEAD
Updating 1a2b3c4..5d6e7f8
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
```

7. git branch:
List, create, or delete branches.

Demo
```bash
sh
$ git branch
* main
  feature-branch
```

8. git checkout:
Switch to a different branch or restore working tree files.

Demo
```bash
sh
$ git checkout feature-branch
Switched to branch 'feature-branch'
```

9. git merge:
Merge changes from one branch into another.

Demo
```bash
sh
$ git merge feature-branch
Updating 1a2b3c4..5d6e7f8
Fast-forward
 file.txt | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
```

10. git status:
Show the working tree status.

Demo
```bash
sh
$ git status
On branch main
Your branch is up-to-date with 'origin/main'.

nothing to commit, working tree clean
```

For more detailed information and advanced usage, check out the official Git documentation.