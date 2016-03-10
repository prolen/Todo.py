# Todo.py
Command line lightweight todo tool with readable storage , written in Py.

## Usage
see `todos --help`

    todos --help
    Usage: todos [OPTIONS]

    Options:
      --version                Show the version and exit.
      --what                   show current use todo file's name
      --use TEXT               use `name` file to store your todos
      --done                   show all done todos
      -n, --new TEXT           new todo
      -c, --complete_ids TEXT  complete todo by id(s) - usage: todos -c 1,2
      -e, --edit TEXT...       edit todo by id - usage: todos -e 2 ``text``
      -r, --remove TEXT        remove todo by id(s)
      --all                    show all todos
      --clear                  clear all todos, need confirm!!
      --help                   Show this message and exit.

## What todo file like
You don't care about this file, `todos` will operate it.

1. [ ] Test todo
2. [ ] Another todo

## Installation
`pip install todos`
