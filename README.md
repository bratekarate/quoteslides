# quoteslides
A slideshow of random quotes in ASCII art.

Quotes are generated with [`fortune`](https://en.wikipedia.org/wiki/Fortune_%28Unix%29) and piped to [`cowsay`](https://github.com/schacon/cowsay) to create ASCII art. Rainbow colors are displayed with [`lolcat`](https://github.com/busyloop/lolcat). 

# Installation
Two options:
1. clone and run (script should run in almost any shell, including `dash`)
2. AUR // todo

# Usage
`quoteslides`

Every 15 seconds a new quote will be displayed with another new cowfile for the ASCII art. Available cowfiles are looped through using roundrobin. 

Skip through quotes by pressing `Enter`.

In case you could not finish reading a quote, previous quotes will be cached in `~/.cache/cowquotes` until next command execution.
