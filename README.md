# crun

A simple Bash helper script that compiles and executes C source files in a single command.

Designed to streamline small projects, quick tests, and daily C programming workflows without needing to write full Makefiles for single-file programs.

## Features

- **One-step execution:** Compiles with `gcc` and immediately runs the binary if compilation succeeds.
- **Flexible output naming:** Automatically names the output binary after the source file by default, or lets you specify a custom binary name.

## Installation

1. **Clone the repository:**
```bash
git clone [https://github.com/Cheddabob420/C-Run.git](https://github.com/Cheddabob420/C-Run.git) cd C-Run && chmod +x crun
```



2. **Add to your PATH:
To run crun from any directory, move it to a directory in your system $PATH (e.g., ~/bin or /usr/local/bin):

```bash
mv crun ~/.local/bin/
```

### Termux

```bash
mv crun $PREFIX/bin/
```