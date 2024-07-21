# dotfiles

## Installation

Prerequsites:

- vim-plug: https://github.com/junegunn/vim-plug

```console
$ curl -fLo $PWD/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

Create symlink:

```console
$ ln -sf ~/src/dotfiles/.vim ~/.vim
```

Then run `:PlugInstall`.

