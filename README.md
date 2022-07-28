# Powerlevel10k

1. Before installing, make sure you remove the old powerlevel10k in your home directory.
    ```zsh
    rm -fr ~/.oh-my-zsh/custom/themes/powerlevel10k
    ```
2. Clone the repository:
    ```zsh
    git clone --depth=1 https://github.com/pnucolab/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
    ```
3. Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`.
