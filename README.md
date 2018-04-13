# My cheat sheet for Debian

Setting up Debian:

Post install:
Installing debian without inserting a password in the root password field will enable sudo command for user.

# Enable ctl+alt+del to open terminal
open start-> settings-> keyboard and add a new key for opening the terminal. Settings for the shortcutt:
     Name:     Terminal
     Command:  gnome-terminal
     Shortcut: ctrl + alt + t
     
     NB, I prefer the XFCE4 terminal, it can be changed to transparent and have a lot of freedom when it comes to settings. (command is      XFCE4-terminal)
  
# update system
    Sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get dist-upgrade
    
# install suggestions in the terminal
    sudo apt-get install command-not-found
    sudo update-command-not-found
    Sudo apt-get install --install-suggests
    
# Setting up Theme and extensions
     # Extension(s)
     Install by going to "Tweak tool" -> Extensions and install the following:
     - Dash to Dock (by michele_g)
     - User theme
     - Hide Activities button (by richardfsr)
     - No topleft hot corner (by azuri)
     - topicon plus
     
     # Themes
     For themes there are a couple i like, go ahead and create the .themes folder and .icons folder in the Home directory. Then download      and add to relevant folder the following themes:
          - Gnome-OS-ll-2-6 (gtk+)
          - macOSX (icons) 
          - Human-BLACK (Shell)
          
     These themes are stored in dropbox.

# Remove application menu from top bar
Go to Tweak tool -> Top bar, and then remove "show application menu"

# Uninstall bloat software

# Install software
