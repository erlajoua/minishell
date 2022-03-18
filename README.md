## Minishell

### Description ✨
**Minishell** is a 42 project, written in C, which consisted in recoding a bash shell and its numerous functionalities.
The execution of several commands (and builtins) with pipes, and redirections `>`, `>>,` `<`.
The **parsing** of commands, the management of **EXIT code**, of some **signals**, and of **environment variables**.

### Main purpose :page_facing_up:
This project taught me a lot of things, first of all the structuring of a big project in C.
A first big part is the parsing of the commands (managing `single quotes`, `double quotes`, `backslash`, `dollars`, etc...)
Another part is the execution of the different commands and the redirections, and builtins. The list of builtins to code is:
- `echo` and the -n option
- `cd` only with a relative or absolute path
- `pwd` without any option
- `export` without any option
- `unset` without any option
- `env` without any option or argument
- `exit` without any option

There is also the management of return codes, as well as the management of `Ctrl+D`, `Ctrl+\`, `Ctrl+C` signals.

This project taught me to run different processes, to manage parsing well, to be structured on how to solve a problem, to test a lot of special cases and to understand how a shell like bash works globally.

### How to use :rocket:
Run the command ``make``, then run:
```
./minishell
```
You can know run the commands you want as, ``ls``, ``echo "Hello World"`` and enjoy!
