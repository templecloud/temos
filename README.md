# TemOS

A personal project containing install scripts, dotfiles, environments, shell functions, and, other useful tidbits.

---

## Usage

* Download and run: `source init.sh`.

* Export TEMOS_HOME: `export TEMOS_HOME=$(pwd)`.

* Ensure `bash dotfiles`. 

    ```bash
    ./dotfiles/bash/activate-bash.sh
    source ~/.bash_profile
    ```

* Ensure `fzf`.

    ```bash
    ./install/fzf/git-install-fzf.sh
    ./dotfiles/fzf/activate-fzf.sh
    ```

* Ensure `ag`.

    ```bash
    yum install -y ag
    ./dotfiles/ag/dot_agignore.sh
    ```

* Ensure `tmux`.

    ```bash
    yum install -y tmux
    ./dotfiles/ag/dot_agignore.sh
    ```

* Ensure `vim`.

    ```bash
    yum install -y vim
    ./dotfiles/vim8/activate-minpac-vim.sh
    # Vim packages installed. If necessary run 'PackUpdate' from inside vim.
    ```

* Ensure `powerline`.

    ```bash
    # yum search fonts | grep powerline
    sudo yum install -y powerline-fonts
    # pip3 install --user --upgrade pip
    # pip3 install --user powerline-status
    # pip3 install --user git+git://github.com/powerline/powerline
    ```

    * https://dev.to/mattstratton/making-powerline-work-in-visual-studio-code-terminal-1m7
    * Original : 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'
    * New      : 'Menlo for Powerline'



---

# References

* [Straus3D dotfiles](https://github.com/Stratus3D/dotfiles/) - A great resource for dotfile projects.