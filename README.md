# vim-settings

##Setup

Add rc files to home or profile directory
MacOS: .vimrc
Windows: _vimrc

##Install

Copy colors to vim folder
```bash
//MacOS
cp -r ./colors $HOME/vim/colors
//Windows
cp -r ./Colors $HOME/vimfiles/colors
```

Install Vundle, run this from root directory
```bash
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

##Install Plugins
Open vim
```bash
vim 
```

Run Vundle Plugin Manager
```bash
:PluginInstall
```
