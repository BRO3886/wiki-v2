# Git
The Holy grail of version control.

## Snippets
- Check files added in the last `{n}` commits
```bash
git show --pretty="" --name-status $(git log -{n} | grep commit | sed 's/commit//') | grep '^A'
```

## Links
* [Git Cheat Sheet](https://www.freecodecamp.org/news/git-cheat-sheet/amp/)
* [Clean/Conventional Commits](https://www.conventionalcommits.org/en/)