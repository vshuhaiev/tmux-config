# tmux-config
Tmux configuration

## Backup old configuration

  ```
  mv ~/.tmux.conf ~/.tmux.conf.bk
  ```

## Installation

  ```
  git clone git@github.com:vshuhaiev/tmux-config.git
  ln -s $(pwd)/tmux-config/.tmux.conf ~/.tmux.conf
  ```

### MacOs fonts
  
  Install [fonts](https://github.com/powerline/fonts/tree/master/Meslo%20Dotted). Details [here](https://www.freecodecamp.org/news/jazz-up-your-bash-terminal-a-step-by-step-guide-with-pictures-80267554cb22/)
  

## Bindings

 - Ctrl-A is used as a prefix
 - Ctrl-A+| split vertically
 - Ctrl-A+- split horizontally

 - vim bindings for moving around and select/yank
 - Ctrl-h/j/k/l for switching panes
