# My Simple Shell

A simple custom shell program written in C that interprets and executes user commands.
This shell can execute commands from the user's environment, handle basic command parsing, and work with environment variables.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Included Libraries] (#stdio.h, stdlib.h, unistd.h, stddef.h, string.h and sys/wait.h)
- [Environment Variables] (#printenv)
- [Contributing] (#Jerry Meletiche)
- [License](#license)
- [Author] (#Francisco Báez)

## Features

- Supports execution of commands in the system's PATH.
- Handles environment variables.
- Basic command parsing and tokenization.
- Simple error handling and reporting.
- Interactive mode with a custom prompt (`#cisfun$ `).
- Exits the shell using the `exit` command, Ctrl + D, Ctrl + C and Ctrl + Z.

## Installation

1. **Clone the repository**:
    ```bash
    git clone git@github.com:Jessy-316/holbertonschool-simple_shell.git
    ```
2. **Navigate into the project directory**:
    ```bash
    cd holbertonschool-simple_shell
    ```
3. **Compile the program**:
    ```bash
    gcc -Wall -Werror -Wextra -pedantic -std=gnu89 shell.c shell.h functions.c -o hsh
    ```
    This will generate the `simple shell` executable.

## Usage

To start the shell, run the following command in your terminal:

```bash
./hsh

