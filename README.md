# dotfiles

## Requirements
* https://github.com/junegunn/fzf
* https://github.com/ajeetdsouza/zoxide

Add `chezmoi.toml`:
```bash
cat ~/.config/chezmoi/chezmoi.toml
[data]
    email = "<email>"
    name = "<Firstname Lastname>"
```

## Install
```bash
sh -c "$(curl -fsLS git.io/chezmoi)" -- init --apply kestoske
```
## Notes
iTerm2 theme: https://github.com/martinlindhe/base16-iterm2