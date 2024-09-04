# Tmux
My custom tmux configuration.

## Requirements
tmux >= 3.1

## Installation

1. Clone this repo and link `tmux.conf` to `~/.tmux.conf`. Note it's a hidden file in this default configuration.
```
ln -sfn /path/to/original/tmux.conf ~/.tmux.conf
```
2. Clone the TPM repo directly into the config folder.
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
3. Reopen terminal or re-source tmux.
```
tmux source ~/.tmux.conf
```

