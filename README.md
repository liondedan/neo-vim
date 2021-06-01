# neo-vim
Setup for neo-vim

## Required
- Node
- Homebrew
- Neovim: `brew install neovim`
- Create the nvim config directory `.config/nvim/init.vim` file at the root directory
- Ag (the silver searcher)
- CoC Prettier - follow the github guide /coc-prettier

## How to setup
- Download this repo, and replace the default `.config/nvim/init.nvm` file with the `nvim/init.nvm`
- Install vim-plug (package manager, make sure the nvim version is selected) 
- Go to `init.vim` file, and run `:PlugInstall`
- Source the file `source %`, re-run `:PlugInstall` (should install CoC)

## Optional
- Install IMB font
- Install Iterm
- Install zsh
- Remap caps lock to escape, this can be done within system > keyboard > modified keys
