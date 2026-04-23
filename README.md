*This project has been created as part of the 42 curriculum by chanin.*

# printf

## Description
printf is a custom implementation of ft_printf, a reduced version of the standard C printf function.

The goal is to handle formatted output using variadic arguments and produce a static library that can be reused in future projects.

Supported conversion specifiers depend on implementation details, typically including:
- c, s, p, d, i, u, x, X, %

## Instructions
### Prerequisites
- cc
- make

### Build
```bash
make
```

This generates:
- libftprintf.a

### Use in another program
```bash
cc -Wall -Wextra -Werror main.c -L. -lftprintf -o my_program
```

### Clean
```bash
make clean
make fclean
make re
```

## Resources
### Documentation
- printf(3): https://man7.org/linux/man-pages/man3/printf.3.html
- stdarg(3): https://man7.org/linux/man-pages/man3/stdarg.3.html
- C variadic arguments: https://en.cppreference.com/w/c/variadic

### Learning references
- Format specifier behavior (printf family): https://en.cppreference.com/w/c/io/fprintf

### AI Usage
AI tools were used for:
- README writing and structure
- Documentation clarity checks
- Review note organization

AI was used as documentation support, not as a replacement for implementation understanding or validation.
