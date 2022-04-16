# dmenu con knos
dmenu is an efficient dynamic menu for X. This contains patches that I've added from suckless.org.

## Patches
* border - Adds a border around dmenu.
* center - Adds an option to center dmenu on screen with `-c`-flag.
* lineheight - Adds an option to increase the height of dmenu with '-h height'-flag.
* lines below prompt - Adds the option to make dmenu list lines vertically below the prompt with '-l lines'-flag.

## Installation
```
sudo make clean install
```

## Configure
Customizations are done in `config.h`, then run `sudo make clean install` to apply those changes.

## Running dmenu
See the man pages for details.
