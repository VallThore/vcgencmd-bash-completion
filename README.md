Bash completion for vcgencmd
============================

This repository contains a simple bash completion script for vcgencmd since RPI doesn't have one. Because as far as my knowledge goes there is no way to query vcgencmd for command's arguments, most of the completions that are provided in this script are based on [official documentation for vcgencmd](https://www.raspberrypi.org/documentation/raspbian/applications/vcgencmd.md). The script was tested on Raspberry Pi 4 on Raspbian Lite distro.

## Installation

1. Clone this repo to a location of your choice, e.g. `git clone https://github.com/VallThore/vcgencmd-bash-completion.git ~/vcgencmd-bash-completion`
2. Copy the `vcgencmd` file from the repo to `/usr/share/bash-completion/completions/`. You can do it by typing `sudo cp ~/vcgencmd-bash-completion/vcgencmd /usr/share/bash-completion/completions/`.
If you **don't want** the system-wide bash completion you can also install it for a local user only, just copy the contents of the `vcgencmd` file to `~/.bash_completion`, e.g. `cat ~/vcgencmd-bash-completion/vcgencmd >> ~/.bash_completion`.
