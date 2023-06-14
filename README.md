# Key Logger

The purpose of this rather simplistic program is to log keys and return them back together with it's keycode value.\
\
Dependencies: stdio.h (printf), ncurses.h\
\
I recommend making an alias in your shell configuration file (bashrc, zshrc, etc.) like follows: alias key="\<path\_to\_program\>", where you obviously define the absolute path to where the program is, which depends on where you cloned it to.\
Example: alias key="~/Documents/github/tools/key\_logger/key\_logger"\
\
This program is open source and free to do whatever with, I won't even ask for credit, I don't care.\
Just note that it requires certain libraries, so you will have to compile with them as well.\
Here's how: gcc key\_logger.c -l ncurses -o key\_logger
