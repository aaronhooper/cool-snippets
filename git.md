# Git snippets

```bash
git update-index --assume-unchanged PATH
```

Prevents git from detecting changes in `PATH`.

```ini
[alias]
lol = log --graph --decorate --pretty=oneline --abbrev-commit --all
```

In `.gitconfig`, this alias transforms your git log into a colorful and
concise output, with a graph display to show forks and merges.

```bash
git log -L LINE_START,LINE_END:FILE
```

Shows the evolution of the block in `FILE` starting at `LINE_START` and
ending at `LINE_END`.

```bash
git checkout --orphan NEW_BRANCH_NAME
```

Creates a new branch with no commits.

```bash
git rebase -i --root
```

Starts an interactive rebase session including the root commit.
