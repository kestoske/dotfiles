# dotfiles

## Requirements
Add `chezmoi.toml`:
```bash
cat ~/.config/chezmoi/chezmoi.toml
[data]
    email = "<email>"
    name = "<Firstname Lastname>"
```

## Install
```bash
sh -c "$(curl -fsLS git.io/chezmoi)" -- init kestoske --apply --ssh
```
## Notes
iTerm2 theme: https://github.com/martinlindhe/base16-iterm2
