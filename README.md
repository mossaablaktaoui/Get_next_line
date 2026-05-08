# get_next_line

## Description
get_next_line is a project about creating a function that reads and returns one line at a time from a file descriptor.

The goal of this project is to understand:
- Static variables
- File descriptors
- Memory management
- Reading from files efficiently

The function must work with files, standard input, and different buffer sizes.

## Prototype

```c
char *get_next_line(int fd);
```

## Instructions

### Compile
```bash
cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 *.c
```

### Example
```c
char *line;

line = get_next_line(fd);
printf("%s", line);
```

## Files
- `get_next_line.c`
- `get_next_line_utils.c`
- `get_next_line.h`

Bonus files:
- `get_next_line_bonus.c`
- `get_next_line_utils_bonus.c`
- `get_next_line_bonus.h`

## Features
- Reads one line at a time
- Handles multiple file descriptors (bonus)
- Works with different BUFFER_SIZE values
- Uses static variables to keep reading state

## Resources
- Linux man pages
- File descriptor documentation
- Static variables in C
- 42 subject PDF

## Notes
This project was written in C following the 42 Norm.

<p align="right"><code>This project was completed in 16 November 2025.</code></p
