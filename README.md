# NeoVim Config

`Linux` `Vim`

Author: Gsharp
Thanksto: theniceboy

## Usage

1. Get [NVIM](https://github.com/neovim/neovim/wiki/Installing-Neovim)
   
   ```sh
   yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm 
   yum install -y neovim python3-neovim
   # you might need python2-neovim as well on older Fedora releases
   ```
2. Check and Update

   ```shell
   cd ~/.config/
   git clone https://github.com/G-sharp/nvim.git
   nvim
   :PlugInstall
   ```

