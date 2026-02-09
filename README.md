<p align="center">
	<img src="https://github.com/ayogun/42-project-badges/blob/main/covers/cover-ft_printf.png" alt="libft_cover" />
</p>

<p align="center">
	<b><i> Because ft_putnbr() and ft_putstr() aren’t enough </i></b>
</p>

<p align="center">
	<img src="https://img.shields.io/badge/Score-100-green?style=none&logo=42" alt="Score project : 100"/>
	<img alt="Static Badge" src="https://img.shields.io/badge/Outstanding-0-blue?style=none&logo=42">
	<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/LeSabreDeDieu/ft_printf?style=none&logo=github">
</p>

## Description
The ft_printf library is a custom implementation of the printf function in the C language. It offers a variety of format specifiers for formatting and displaying data in a flexible manner.

## Project structure
The project is organized as follows :

```
.
├── includes
│   ├── ft_printf.h
│   └── libft.h
├── libft
│   ├── ft_is
│   ├── ft_lst
│   ├── ft_mem
│   ├── ft_put
│   ├── ft_str
│   ├── ft_to
│   └── Makefile
├── Makefile
└── srcs
    ├── ft_printf.c
    ├── ft_printf_utils.c
    ├── ft_print_hex.c
    ├── ft_print_ptr.c
    └── ft_print_unsigned.c
```

The project contains an `includes` folder for header files, a `libft` folder with library modules, a `Makefile` file for compiling the project, and an `srcs` folder with the library source files.

## Compilation
To compile the ft_printf library, use the `Makefile` file at the root of the project. Run the following command in the terminal:
```bash
make all
```

This will generate the `libftprintf.a` library in the root directory.

## Usage
To use the ft_printf library in your project, include the `ft_printf.h` header file in your source files, and compile your project by linking with the `libftprintf.a` library.

Compilation example :
```bash
gcc -o mon_programme mes_sources.c -L. -lftprintf
```

## Auteur
sgabsi
