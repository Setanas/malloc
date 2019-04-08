# Malloc

Malloc is one of the second year project in Epitech. <br/>
First of all, what is malloc, malloc is a function from the C standard library which allows you to allocate memory dynamicly.
In this project we had to re-code a shared library containing malloc, free and realloc functions.<br/>

## Getting Started

This library is programmed in C on a Linux environment.<br/>

### Prerequisites

To compile we are using gcc.<br/>

### Installing

To compile the library please use the Makefile
 
```
$> make
```

At the end you should have a "libmy_malloc.so" shared library in your current folder.

## Running a program with the library.

To try the library on a simple program :<br/>

```
$> LD_PRELOAD=./libmy_malloc.so {program name}
```

You can put the library in your environment so you don't need to do "LD_PRELOAD=..." in front of every program you want to try :

```
$> export LD_PRELOAD=path/to/the/lib/libmy_malloc.so
```

## Authors

* **Sébastien Tan** - *Developer* - [Setanas](https://github.com/Setanas)
