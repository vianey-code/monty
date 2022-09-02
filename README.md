# MONTY

![alt text](https://pbs.twimg.com/media/CFYYWy6UEAE9Ow-.png)

## Description

Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files. [Monty](http://montyscoconut.github.io/) is a language that aims to close the gap between scripting and programming languages.

*****

## Installation

1. Clone this repository:
```console
https://github.com/Succynice/monty.git
```

## Usage
1. Enter at directory
```console
cd monty
```

2. Compile:
```console
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
```

3. Execute:
```console
./montyfile opcodetestfile.m
//The opcodetestfile contains the bytcode instructions for example
cat -e 000.m
push 0$
push 1$
push 2$
  push 3$
                   pall    $
push 4$
    push 5    $
      push    6        $
pall$
```

4. Exit status:
```console
Exits with status EXIT_FAILURE
```
## Functions

The functions used are:

|Name | Description | Return| File
|:--: | :-- | :--| :--|
| add | adds the top two elements of the stack | No Return | add.c|
| addnode | add node to the head stack | No Return | addnode.c|
| div | divides the top two elements of the stack. | No Return | div.c|
| execute | executes the opcode | No Return | execute.c|
| free_stack | frees a doubly linked list | No Return | free_stack.c|
| main | monty code interpreter | 0 on success | main.c|

## Compilation
All files were compiled on Ubuntu `20.04 LTS.`

All programs and functions were compiled with `gcc 4.8.4` using flags `-Wall -Werror -Wextra and -pedantic`.

## Styling
All files have been written in the `Betty Style.`

*****

## Authors
[CHIKEZIE SUCCESS](https://github.com/Succynice) and [EREM CHINEDU](https://github.com/alextindey)
