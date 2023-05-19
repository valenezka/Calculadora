# Git and GH workflow

## Git

### Git commands

#### Git config

```bash
git config --global user.name "John Doe"
git config --global user.email "johndoe@mail.com"
```

#### Git init

```bash
git init
```

#### Git clone

```bash
git clone <GITHUB_LINK>
```

### Git add

```bash
git add <FILE_NAME>
```

**_ Note: _** `git add .` adds all files in the current directory

### Git commit

```bash
git commit -m "Commit message"
```

**_ Note: _** `git commit -am "Commit message"` adds all files in the current directory and commits them.
**_ Note: _** There exists something called conventional commits. It is a standard for commit messages. It is a good practice to follow it. [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

### Git push

```bash
git push origin <BRANCH_NAME>
```

### Git pull

```bash
git pull origin <BRANCH_NAME>
```

### Git status

```bash
git status
```

### Git log

```bash
git log
```

### Git checkout

```bash
git checkout <BRANCH_NAME>
```

**_ Note: _** `git checkout -b <BRANCH_NAME>` creates a new branch and switches to it.

### Git remote

```bash
git remote add origin <GITHUB_LINK>
```

**_ Note: _** `git remote -v` shows the remote repository.
