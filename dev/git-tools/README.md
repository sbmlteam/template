Git hooks for SBML team repositories
====================================

The subdirectory [hooks](hooks) contains some suggested `git` hook programs to implement some useful best practices.  They need to be added to the `.git/hooks` subdirectory at the root of your local copy of the repository.  One way to do this is to execute the following commands in a shell terminal (where the paths here are shown **relative to the current directory**):

```csh
cd ../..
mkdir -f .git/hooks
cd .git/hooks
ln -s ../dev/git-tools/hooks/*
```

Origins of the programs in the `hooks` subdirectory
---------------------------------------------------

* [hooks/pre-commit](hooks/pre-commit): This originally came from the repository [git-pre-commit-hook-windows-filenames](https://github.com/t-b/git-pre-commit-hook-windows-filenames), by Thomas Braun.  The modification date at the time the script was copied was 2013.  The script is copyright (C) 2013 Thomas Braun.  No distribution terms are included with the repository.
