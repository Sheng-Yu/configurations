# Configurations
This is a repository for my personal configurations for zsh, vim, and screen.

## Included Packages
### For zsh
- [bhilburn/powerlevel9k](//github.com/bhilburn/powerlevel9k)

### For vim
- [VundleVim/Vundle.vim](//github.com/VundleVim/Vundle.vim)
- [w0rp/ale](//github.com/w0rp/ale)
- [scrooloose/nerdtree](//github.com/scrooloose/nerdtree)
- [Xuyuanp/nerdtree-git-plugin](//github.com/Xuyuanp/nerdtree-git-plugin)
- [vim-airline/vim-airline](//github.com/vim-airline/vim-airline)
- [airblade/vim-gitgutter](//github.com/airblade/vim-gitgutter)
- [valloric/youcompleteme](//github.com/valloric/youcompleteme)

## Installation Steps
1. Install [Oh My Zsh][oh-my-zsh].
2. Install [vim][] 8 with Python supported. (You might need to compile this yourself.)
3. Install `.zshrc` and `.vimrc`.
4. Install vim plugins.

### Build Vim from Source
Please refer https://github.com/Valloric/YouCompleteMe/wiki/Building-Vim-from-source.

### Install Configuration Files
```sh
wget https://raw.githubusercontent.com/cyliang/configurations/master/.zshrc -O ~/.zshrc
wget https://raw.githubusercontent.com/cyliang/configurations/master/.vimrc -O ~/.vimrc
```

### Install Vim Plugins
#### Install most plugins
1. Open vim.
2. Type `:PluginInstall` and wait for the installation until `done` is printed.

#### Install YouCompleteMe
Please refer https://github.com/Valloric/YouCompleteMe#ubuntu-linux-x64.


[oh-my-zsh]: http://ohmyz.sh/
[vim]: https://github.com/vim/vim
