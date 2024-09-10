# Dots

## Overview

I used to store all of my dotfiles in a monorepo. That quickly became unsustainable; so I'm
going to try again with various dotfiles stored in the respective git repos as required and
then added as submodules here.

### Applications

- Alacritty
- Atuin
- Neovim
- ZSH
- Starship
- FZF
- Tmux
- Zellij
- Hammerspoon


### Environments

- MacOS
- Debian/Ubuntu
- Codespaces
    - Installation/Configuration Scripts
    - Dockerfiles


## Structure

    .
    ├── alacritty                       # mvandermeulen/alacritty
    ├── atuin                           # mvandermeulen/atuin
    ├── environments                    # mvandermeulen/environments
    │   ├── darwin                      #
    │   └── linux                       #
    ├── codespace                       # mvandermeulen/codespace
    ├── neovim                          # mvandermeulen/nvim
    ├── shell                           # mvandermeulen/vandershell
    ├── ssh                             # mvandermeulen/ssh_config
    ├── starship                        # mvandermeulen/starship_config
    ├── tmux                            # mvandermeulen/tmux_config
    ├── tmuxp                           # mvandermeulen/tmuxp_config
    ├── tools                           # mvandermeulen/dot_tools
    ├── vanderhammer                    # mvandermeulen/vanderhammer
    ├── zsh                             # mvandermeulen/dot-zsh
    └── README.md                       # This file

> Use short lowercase names at least for the top-level files and folders except
> `LICENSE`, `README.md`




