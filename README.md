# SublimeText2 Settings

This repo contains all my -- [Dana Woodman](http://danawoodman.com) -- Sublime Text 2 settings, themes and packages.

## Setup

1. Clone this repo somewhere (I prefer Dropbox).

        mkdir -p ~/Dropbox/Programs/SublimeText2/Packages
        git clone https://github.com/danawoodman/sublime.git ~/Dropbox/Programs/SublimeText2/Packages/User

2. Install Sublime Text 2
3. Remove the `User` folder in the `Packages` folder. *Make sure to back it up, especially if you have settings there!*

        rm -rf ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User

4. Make a symbolic link between this new repo and the Packages folder.

        ln -s ~/Dropbox/Programs/SublimeText2/Packages/User ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User

5. Install [Package Control](http://wbond.net/sublime_packages/package_control/installation) and restart Sublime.
6. ???
7. Profit!
