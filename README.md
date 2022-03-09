```

           ________  ________  _________  ________ ___  ___       _______   ________      
          |\   ___ \|\   __  \|\___   ___\\  _____\\  \|\  \     |\  ___ \ |\   ____\     
          \ \  \_|\ \ \  \|\  \|___ \  \_\ \  \__/\ \  \ \  \    \ \   __/|\ \  \___|_    
           \ \  \ \\ \ \  \\\  \   \ \  \ \ \   __\\ \  \ \  \    \ \  \_|/_\ \_____  \   
            \ \  \_\\ \ \  \\\  \   \ \  \ \ \  \_| \ \  \ \  \____\ \  \_|\ \|____|\  \  
             \ \_______\ \_______\   \ \__\ \ \__\   \ \__\ \_______\ \_______\____\_\  \ 
              \|_______|\|_______|    \|__|  \|__|    \|__|\|_______|\|_______|\_________\
                                                                              \|_________|
                                  Personal dotfiles of MkHunter
                                  
```

# Dotfiles

## Used Applications

- **Distro:** Debian
- **Shell:** [Fish](https://github.com/iamsamiulazim/Dotfiles/tree/main/.config/fish)
- **Starship:** [(Starship Prompt)](https://github.com/iamsamiulazim/Dotfiles/blob/main/.config/starship.toml)

## Installation
```
#create a folder in your home directory
mkdir dotfiles

#clone this github repository as bare
git clone --bare https://github.com/MkHunter/dotfiles.git $HOME/dotfiles

#define the alias in the current shell scope.
alias dotfiles='/usr/bin/git --git-dir=$HOME/dotfiles/ --work-tree=$HOME'

#run this command if the alias is placed correctly in your shell.
dotfiles config --local status.showUntrackedFiles no

#checkout the actual content from the git repository to your $HOME
dotfiles checkout
```
