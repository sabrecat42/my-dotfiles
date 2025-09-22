# Dotfiles Management

This repository contains configuration files (dotfiles) for both user and global environments.

- To install **user** dotfiles, run:
    ```
    stow -t ~ user
    ```

- To install **global** dotfiles, run:
    ```
    cd global
    stow -t /etc etc
    ```
