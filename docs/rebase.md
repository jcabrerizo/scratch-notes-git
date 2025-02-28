# git rebase

## interactive

[Docs](https://git-scm.com/docs/git-rebase#_interactive_mode.

Use `git rebase -i $AFTER_THIS_COMMIT` and replace `pick` on the **second** and subsequent commits with `squash` (`s`)

```shell
git rebase -i ${AFTER_THIS_COMMIT:?"which commit?"}
```