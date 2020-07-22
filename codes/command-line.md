# Command Line

## Filepaths

|                 |                                                               |
| --------------- | ------------------------------------------------------------- |
| `img/logo.png`  | Relative path: resolved realtive to current working directory |
| `/usr/bin/bash` | Aboslute path: resolved relative to the file system root      |
| `.`             | Current working directory                                     |
| `..`            | Parent directory                                              |
| `~`             | User home directory                                           |

## Browsing the file system

|                  |                                                                        |
| ---------------- | ---------------------------------------------------------------------- |
| `pwd`            | Print working directory                                                |
| `cd`             | Change working directory                                               |
| `cd <path>`      | Change working directory + path                                        |
| `cd`             | Change working directory to home directory, equivalent to 'cd ~'       |
| `ls <path>`      | list all the folders and files in the specified path                   |
| `ls`             | list all folders and files in current directory                        |
| `ls -l`          | list long format, including file permissions, owner, change date, size |
| `ls -a`          | list show hidden files starting with .                                 |
| `cat`            | Print <file> to standard out interpreted as plain text                 |
| `hexdump <file>` | Print bytes in 'file' using hexadecimal digits                         |
| ---------------- | ---------------------------------------------------------------------- |
|                  |