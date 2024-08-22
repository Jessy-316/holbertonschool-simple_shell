# My Simple Shell

A simple custom shell program written in C that interprets and executes user commands.
This shell can execute commands from the user's environment, handle basic command parsing, and work with environment variables.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Included Libraries](#included-libraries)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [Author](#author)

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
    gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
    ```
    This will generate the `hsh` executable.

## Usage

To start the shell, run the following command in your terminal:

```bash
./hsh
```

## Commands

exit - Exits the shell.
env - prints the environment.

## Included Libraries

- #include <stdio.h>
- #include <stdlib.h>
- #include <unistd.h>
- #include <stddef.h>
- #include <string.h>
- #include <sys/wait.h>

## Environment Variables

The shell utilizes environment variables defined by the system. 
You can access these variables using the '_getenv' function.

** Example of accessing the 'PATH' environment variable** :
    ```bash
    char *path = _getenv("PATH");
    ```

## Contributing

Contributions are welcomed!
If you would like to contribute to this project, please follow these steps:

1. **Clone the repositoriy.**

2. **Create a new branch**
    ```bash
    git checkout -b feature-branch
    ```
3. **Make your changes and commit them**
    ```bash
    git commit -am 'Added new feature'
    ```
4. **Push to the branch**
    ```bash
    git push origin feature-branch
    ```
5. **Make a pull request**

## Author

**Francisco Antonio Báez López**
**Jerry Luis Meletiche Baerga**

