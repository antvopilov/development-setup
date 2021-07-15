# [Atom.io](https://atom.io/) - hackable text editor

## Install

```bash
brew install atom
```

## Editor Config

Use Git to version control your config file (`~/.atom/config.cson`).

Host your Git repository on GitHub, and retrieve it by running `git clone https://github.com/{username}/{repo}`.

Keep it up to date using `git push` (to upload changes) and `git pull` (to download changes).


## Track Installed Packages

- Export `apm list --installed --bare > ~/.atom/package.list`
- Restore `apm install --packages-file ~/.atom/package.list`
