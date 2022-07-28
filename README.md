# Powerlevel10k

1. Make sure you already installed oh-my-zsh: https://ohmyz.sh/
2. Make sure to remove the old powerlevel10k in your home directory.
    ```zsh
    rm -fr ~/.oh-my-zsh/custom/themes/powerlevel10k
    ```
2. Clone the repository:
    ```zsh
    git clone --depth=1 https://github.com/pnucolab/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
    ```
3. Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`.
