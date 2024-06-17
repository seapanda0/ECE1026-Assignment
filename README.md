# Flights data manager in C w/ ncurses

External libraries used:

- [ncurses](https://invisible-island.net/ncurses/man/ncurses.3x.html)
- regex (Packaged with POSIX systems)

## Compiling

- Debian:

  ``` bash
  git clone https://github.com/seapanda0/ACE6123-Assignment
    
  sudo apt install libncurses5-dev

  cd ACE6123-Assignment/

  gcc -o main main.c -lncurses
  ```

## Running

  After compiling, type `./main` in your terminal to start the program.

## Using the program

At start, the program will prompt you for the database text file. You need to enter a comma-separated value file in `.txt` extension. The file needs to be in your current working directory. Refer to [`dataset.txt`](dataset.txt) above for sample dataset.

Use left/right arrow keys to navigate through the menu options, Up/down arrow keys or mouse scroll wheel to navigate through the data list.

## Features
 - File validation using regular expressions
 - Search by flight number, origin and destination
 - Sort by all attributes
 - Add entry at the botton of the dataset
 - Insert entry at a specific line
 - Delete a specific entry
 - Update a selected entry
 - Input validation using regular expressions
 - Save file

## Screenshots

![Running][ss-1]

![GIF of program][ss-2]

[ss-1]:https://i.imgur.com/ktOytH7.gif "GIF 1"

[ss-2]: https://i.imgur.com/t7SzATU.gif "GIF 2"
