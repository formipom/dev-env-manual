# dev-env-manual

Installation manual to set an environemnt.

### Installation

Install zsh, oh-my-zsh.

    $ sudo apt install zsh -y && chsh -s `which zsh`
    $ curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh

Install dependency packages for plugins of vim-plug.

    $ sudo apt install build-essential cmake python3-dev
    $ sudo apt install fonts-powerline xclip autojump
    $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    $ git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

Move configuration files to `HOME` directory.

    $ mv .zshrc .tmux.conf .tmux.conf.local ~/

Restart shell

