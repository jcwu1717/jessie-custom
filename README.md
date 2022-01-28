jessie-custom Terminal Theme
==================

### Description

This is my Mac terminal profile and configuration for default macos terminal.app .
The custom terminal theme is edited from the file:`$ZSH/themes/alanpeabody`

Created: 2021-08-11

### Usage
1. Install `zsh` . Change the default shell to zsh in your terminal setting. 
   If using Mac OS, the zsh now is default shell.

   If not Mac OS, do this:
    `sudo chsh -s $(which zsh) $(whoami)`
2. Install `oh-my-zsh` via curl
    `sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
3. Copy the file `jessie-custom.zsh-theme` to `$ZSH_CUSTOM/themes`.
    
    The path of $ZSH_CUSTOM can be found by running ` echo $ZSH_CUSTOM` in the terminal.
3. Change `.zshrc` file
    In the file, edit `ZSH_THEME="jessie-custom"` and save it.
4. Reopen a terminal and you will see the **jessie-custom** terminal theme!

### oh-my-zsh Color Code
* $`cd ~/.oh-my-zsh/lib`
* $`spectrum_ls`
You can see the color code preview in the terminal.
