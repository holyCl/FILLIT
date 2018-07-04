# Fillit
A program that takes a list of Tetriminos and create with them the smallest square possible

## Fillit - a program that takes a list of Tetriminos and create with them the smallest square possible

### Description:

Fillit is a project that helps to discover a recurring problematic in programming: 
searching the optimal solution among a huge set of possibilities, in a respectable timing.
In this particular project, the aim is to find a way to assemble a given Tetriminos set altogether in the smallest possible square.

A Tetriminos is a 4-blocks geometric figure most people probably already heard of, thanks to the popular game Tetris.

Please find full description of the project in [this subject](https://github.com/Navalag/fillit/blob/master/fillit.en.pdf).

### Goals:

Fillit is not about recoding Tetris, even if it’s still a variant of this game.
This program take a file as parameter, which contains a list of Tetriminos, and arrange them in order to create the smallest square possible.

Main goal is to find the smallest square in the minimal amount of time, despite an exponentially growing number of possibilities each time a piece is added.

### How To Launch And Test:

First clone git repository (type in console):

```

git clone https://github.com/Navalag/fillit.git

```

Than go to the project folder and launch:

```

cd fillit

make

```

Now you can test it with your own tests or use one from this repo:

```

./fillit [test_file.txt (or your own test file)]

```
