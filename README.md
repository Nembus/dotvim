# To Install

This is mostly a clone of Pivotal Lab's configuration:
git@github.com:pivotal/vim-config.git


(Re)move ~/.vim and ~/.vimrc if you have them already, and run:
    git@github.com:Nembus/dotvim.git
    cd ~/.vim
    git submodule update --init
    ln -s ~/.vim/vimrc ~/.vimrc

# Updating

As long as your checkout is kept clean, you can easily update, rebase your local changes and update submodules with:

    cd ~/.vim && git pull --rebase ; git submodule update ; cd -
