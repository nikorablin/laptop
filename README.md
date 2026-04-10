# New Mac Setup

## Run script

```sh
sh ./mac
```

The `mac` script installs the base command line tooling and then runs
`laptop.local` when that file is present.

## Base Setup

`mac` installs and configures:

- Homebrew
- zsh as the login shell
- `$HOME/.bin` on the shell `PATH`
- Git
- GitHub CLI (`gh`)
- tmux
- vim
- Fast Node Manager (`fnm`)
- The latest LTS Node.js release via `fnm`

## Local Laptop Setup

`laptop.local` expects Homebrew, Git, curl, and unzip to be available. It
installs:

- Google Chrome
- Slack
- iTerm2
- Firefox
- VLC
- Visual Studio Code
- 1Password
- Zoom
- WhatsApp
- Ghostty
- Numi
- Logi Options+
- Fira Code font
- Codex CLI
- dockutil

It also configures:

- Global Git identity and defaults
- Oh My Zsh
- Spaceship prompt
- `git-open`
- `zsh-autosuggestions`
- `zsh-syntax-highlighting`
- Dotfiles from `nikorablin/dotfiles`
- iTerm2 preferences to load from `$HOME/dotfiles`
- Dock apps: Google Chrome, Messages, Music, iTerm2, Visual Studio Code, and WhatsApp
