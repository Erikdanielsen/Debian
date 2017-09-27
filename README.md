# My cheat sheet for Debian

Setting up Debian:

Before install:
- Installing debian without inserting a password in the root password field will enable sudo command for user.

# Enable ctl+alt+del to open terminal
open start-> settings-> keyboard and add a new key for opening the terminal. Settings for the shortcutt:
     Name:     Terminal
     Command:  gnome-terminal
     Shortcut: ctrl + alt + t
  
# update system
    Sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get dist-upgrade
    
# install suggestions in the terminal
    sudo apt-get install command-not-found
    sudo update-command-not-found
    Sudo apt-get install --install-suggests
