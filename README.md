# init.vim for Neovim

## dependencies

### vim-plug
init.vim using vim-plug for plugin manager.
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
https://github.com/junegunn/vim-plug


### Install Plugins
```
#open nvim and hit this command below
:PlugInstall
```

### nodejs
coc.nvim need nodejs for Language server
```
#Mac
brew install nodejs 
#Ubuntu
curl -fsSL https://deb.nodesource.com/setup_17.x | sudo -E bash -
sudo apt-get install -y nodejs
```

### Setup haskell Language Server
https://github.com/neoclide/coc.nvim/wiki/Language-servers#haskell

### nerd fonts
fern needs nerd icon for colord file name and funcy icons.
https://www.nerdfonts.com/
