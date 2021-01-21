# [Delta](https://github.com/dandavison/delta)

| Distribution | Package     |
| ------------ | ----------- |
| Fedora       | `git-delta` |
| Homebrew     | `git-delta` |

Config in git:

```sh
git config --global core.pager delta

git config --global delta.syntax-theme YourFavoriteTheme
```

Edit in `~/.bashrc`, `~/.zshrc`:

```sh
export DELTA_PAGER=bat
```