---
layout: posts
title: Git--Basic
tags:
  - Git
  - commands
date: 2024-07-30 19:49:27
---

### Basic

- **Initialize a new Git respository**

```bash
git init
```

- **Delete the entire `.git` directory**

```bash
rm -rf .git
```

- **Clone a repository into current directory**

```bash
git clone . [gitURL]
```

- **Fetch and merge changes**

```bash
git pull origin [branchName]
```

- **Push changes**

```bash
git push origin [branchName]
```

### Branch

- **List all branches**

```bash
git branch
```

- **Create a new branch**

```bash
git branch [branchName]
```

- **Create and switch to a new branch**

```bash
git checkout -b [branchName]
```

### Remote

- **List remote respositories**

```bash
git remote -v
```

- **Add a new remote respository**

```bash
git remote add [remoteName] [remoteURL]
```

- **Remove a remote respository**

```bash
git remote rm [remoteName]
```
