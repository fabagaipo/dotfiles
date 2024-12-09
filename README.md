# Dotfiles

Config files for the tech I use:
- [Bash](https://www.gnu.org/software/bash/)
- [Bashtop](https://github.com/aristocratos/bashtop)
- [Hyper Terminal](https://hyper.is/)
- [ncspot](https://github.com/hrkfdn/ncspot)
- [Spicetify](https://spicetify.app/)
- [Vencord](https://vencord.dev/)
- [Zsh](https://www.zsh.org/)
    - [oh-my-zsh](https://ohmyz.sh/)
    - [power10k](https://github.com/romkatv/powerlevel10k)
    - [zsh plugins](https://github.com/unixorn/awesome-zsh-plugins)

# Symlink dotfiles to local files

## Manual symlinking

  Linux command:

    
    ln -sf ~/dotfiles/$file ~/.$file
 

## Script symlinking

  (WIP) Instructions:
        
    cd ~/dotfiles
    chmod +x makesymlinks.sh
    ./makesymlinks.sh

  Note:
  
  - Files are currently hardcoded in `makesymlinks.sh`, feel free to replace them with your own dotfiles 
    
  - If local dotfiles are stored in inner folders and are not found directly in `$HOME` directory then do not include them in the script (this edge case will be handled in future iteration *i think*), proceed with manual symlinking instead for these cases
