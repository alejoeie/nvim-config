# Alejoeie nvim config

Hi there! It has been a while that I have been searching for an optimal
IDE for developing my projects and assignments both at work or at personal 
commitments. So, checking, inquiring on how to get the best IDE, I decided 
nvim has everything to jump into a better development experience. 

It is a complicated ramp up process, but when you realize, your development shortcuts
gets faster, easier and funnier than developing on custom IDE such as VSCode, SublimeText
or whatever. That is why, I decided to take my time into glowing up my personal neovim 
features, and here is what I have for the moment. 

I add some of the features installed for you to have a better knowledge on the vast
world of tools neovim has.

## Plugins installed (Used Packer.nvim)

* Fuzzy Finder: [Telescope](https://github.com/nvim-telescope/telescope.nvim)
* Color Theme: [rose-pine](https://github.com/rose-pine/neovim)
* Packer: [Packer](https://github.com/wbthomason/packer.nvim)
* Tree Explorer: [Treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
* Branch Manager: [Undotree](https://github.com/mbbill/undotree)
* Shortcuts system: [ThePrimeagen](https://github.com/ThePrimeagen/init.lua/tree/master)

## Requirements
- You need to be running **Neovim v0.5.0+**
- If you are on Windows, you need developer mode enabled in order to use local plugins (creating symbolic links requires admin privileges on Windows).

## Installation
``` shell
git clone https://github.com/alejoeie/nvim-config
```

Set it as your default nvim file inside **.config/**
Cd into **lua/primagen/init.lua and :so inside nvim to run all config.
