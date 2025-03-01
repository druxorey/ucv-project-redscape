<h1 align="center">Project Redscape</h1>

## **Overview**
Project Redscape is an exciting text-based card game, developed in C++ for [TheGame.cpp](https://henrzven.github.io/the-game/). Immerse yourself in a world of where you must use your wits and strategy to win.

## Compilation / Execution
To compile the program you can use the Makefile, but you need to have make installed and set on your env variables.
You can use this method by typing "make all start". This will compile and execute the game.

In case you don't have make, you can compile and run manually with g++, with this two commands:

```bash
g++ -o build/redscape -Iinclude main.cpp src/cards.cpp src/cutscenes.cpp src/utils.cpp src/combats.cpp src/engine.cpp 
```

```bash
./build/redscape

```

## Development Guide
This document provides guidelines for the project development. For more details, refer to the [Development Document](docs/DEVELOPMENT.md).

## Contribute
If you want to add new functionalities or improve existing ones, follow these steps:

1. Open an issue to discuss the changes.
2. Fork this repository.
3. Create a new branch for your contribution: `git checkout -b your-branch-name`.
5. Commit your changes, for example: `git commit -m 'fix: new changes'`.
6. Push your changes to your forked repository: `git push origin your-branch-name`.
7. Open a Pull Request in this repository and reference the original issue.

## Development Team

| [![Druxorey](https://github.com/druxorey.png?size=100)](https://github.com/druxorey) | [![Santiago](https://github.com/santiago-commit.png?size=100)](https://github.com/santiago-commit) |
| - | - |
| [Druxorey](https://github.com/druxorey) | [Santiago](https://github.com/santiago-commit)

## License

This project is licensed under the GPL-3.0 License. See the [LICENSE](LICENSE) file for more details.
