**IMPORTANT** Requires [Neovim v0.6.0](https://github.com/neovim/neovim/releases/tag/v0.6.0). 
```
sudo add-apt-repository ppa:neovim-ppa/stable
sudo apt update
sudo apt install neovim
git clone https://github.com/ernestyyy0306/NeoVim.git ~/.config/nvim
```

Run `nvim` and wait for the plugins to be installed 

**NOTE** (You will notice treesitter pulling in a bunch of parsers the next time you open Neovim) 

## Get healthy

Open `nvim` and enter the following:

```
:checkhealth
```

## Dependencies

  ```
  sudo apt install unzip fd-find ripgrep xsel npm xorg openbox python3-pip libx11-dev libxext-dev
  pip3 install pynvim 
  pip3 install ueberzug
  gh - https://github.com/cli/cli/blob/trunk/docs/install_linux.md
  node - https://github.com/Schniz/fnm
  ```
