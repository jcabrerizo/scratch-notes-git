# Git

## Tricks

### Remove ignored files

Notice `--dry-run` shows what would be deleted if removed

```shell
git clean -f -x -d --dry-run 
```

### Show files modified on commit
```shell
 git diff-tree --no-commit-id --name-status $COMMIT_HASH
```