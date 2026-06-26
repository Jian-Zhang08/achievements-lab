# Git tips

A short collection of safe-by-default Git commands.

- `git reset --soft HEAD~1` — undo the last commit, keep changes staged.
- `git push --force-with-lease` — force-push that refuses to clobber unseen upstream work.
- `git rebase -i main` — squash WIP commits into one clean commit before review.
