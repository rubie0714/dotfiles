# Dotfiles

> My config files

## Install

1. Auto install: `curl -sL https://raw.githubusercontent.com/rubie0714/dotfiles/master/setup.sh | sh`
2. Manual install:
    1. Clone this repo: `git clone https://github.com/rubie0714/dotfiles ~/.dotfiles`.
    2. Run setup script: `sh ~/.dotfiles/setup.sh` or link config file to the right place by yourself.

## Setup

- Create `.gitconfig.user` in your home dir or move `.gitconfig.user-example` to home dir
- Example content
    ```
    [user]
        email = arthurc0102@gmail.com
        name = Arthur Chang
    ```

## Hint

- Run `antigen cache-gen` after config, to speed up terminal startup
