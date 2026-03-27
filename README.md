# My dotfiles

This repository provides a backup of my configuration (my Linux dotfiles) to allow the restore of my desktop environment across multiple builds etc.

# Scope

This repository contains configuration for
 - Alacritty (providing the Catppuccin theming and font updates)
 - Applications (primarily updating the .desktop files to hide applications I don't want to see)
 - Fuzzel (providing Catppuccin mocha theming and sizing)
 - Git (providing my name and email)
 - Mako (providing Catppuccin theming)
 - Niri (providing configuration for my window manager)
 - Oh My Posh (Adds further theming to zsh)
 - Swaylock (providing theming for my lock screen)
 - Waybar (setup and theming for my top bar)
 - Wallpapers (this will place my wallpapers in Pictures/Wallpaper)

 # Usage

 This repository must be cloned to the home directory. The files can then be used with GNU Stow using the command 
 
 ```bash
 stow <project name>
 ```

 If configuration is already in place you may need to remove it or use 

 ```bash
 stow --adopt <project name>
 ```