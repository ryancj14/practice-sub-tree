# practice-sub-tree
This repository is for practicing adding a subtree

This is the command used to include the subtree
```
git subtree add --prefix third_party/common-config https://github.com/ryancj14/common-config main --squash
```

git subtree help
```
(base) Ryans-Air-2:practice-sub-tree ryanjohnson$ git subtree
usage: git subtree add   --prefix=<prefix> <commit>
   or: git subtree add   --prefix=<prefix> <repository> <ref>
   or: git subtree merge --prefix=<prefix> <commit>
   or: git subtree pull  --prefix=<prefix> <repository> <ref>
   or: git subtree push  --prefix=<prefix> <repository> <ref>
   or: git subtree split --prefix=<prefix> <commit>

    -h, --help            show the help
    -q                    quiet
    -d                    show debug messages
    -P, --prefix ...      the name of the subdir to split out
    -m, --message ...     use the given message as the commit message for the merge commit

options for 'split'
    --annotate ...        add a prefix to commit message of new commits
    -b, --branch ...      create a new branch from the split subtree
    --ignore-joins        ignore prior --rejoin commits
    --onto ...            try connecting new tree to an existing one
    --rejoin              merge the new branch back into HEAD

options for 'add', 'merge', and 'pull'
    --squash              merge subtree changes as a single commit
```