Say you need to get Vim really quick, but you don't know how to use it. I'm gonna teach you.

You probably got to install it, so run these commands:

> Debian-based:
`sudo apt-get install vim -y && cd && echo "set number" > .vimrc && cd -`

> Arch-based:
`sudo pacman -Sy vim && cd && echo "set number" > .vimrc && cd -`

> RHEL-based:
`sudo yum install vim && cd && echo "set number" > .vimrc && cd -`

> Windows (as admin):
`choco install vim-tux`

First, to get the functionality of Nano, you just need to learn these commands:

> `i` - get into insert mode where you can type text

> [ESC] - get out of insert mode

> `:q` or `q` (depends, try both) - quit out of Vim.
