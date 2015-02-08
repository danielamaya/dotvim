## Requirements
- ctags (apt-get install ctags, yum install ctags, pacman -S ctags)

## Install

    git clone git://github.com/danielamaya/dotvim.git .vim
    cd .vim
    ln -s ~/.vim/vimrc ~/.vimrc

### Install Vundle

  git
  clone
  https://github.com/gmarik/Vundle.vim.git
  ~/.vim/bundle/Vundle.vim

### Install other plugins using vundle

  Open up vim, type :BundleInstall

## Customization

    ~/.vim/vimrc.$USER

If your shell login is *purl*, create the file *~/.vim/vimrc.purl*.

All custom vim configuration will override the dotvim defaults.
