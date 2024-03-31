# Monty

This repository contains the source code for a Monty interpreter, which is capable of interpreting Monty ByteCodes files.

## Files

- `main.c`: Main entry point of the Monty interpreter.
- `monty.h`: Header file containing function prototypes and data structure definitions.
- `opr_add.c`: Implementation of the `add` opcode.
- `opr_div.c`: Implementation of the `div` opcode.
- `opr_free_stack.c`: Function to free the stack.
- `opr_mul.c`: Implementation of the `mul` opcode.
- `opr_pall.c`: Implementation of the `pall` opcode.
- `opr_pint.c`: Implementation of the `pint` opcode.
- `opr_pstr.c`: Implementation of the `pstr` opcode.
- `opr_queue.c`: Implementation of the `queue` opcode.
- `opr_rotr.c`: Implementation of the `rotr` opcode.
- `opr_sub.c`: Implementation of the `sub` opcode.
- `tests/`: Directory containing test cases for the Monty interpreter.
- `bf/`: Directory containing Brainf*ck scripts used for testing.

## Usage

To run the Monty interpreter, use the following command:

./monty <file_name>

Replace `<file_name>` with the path to the Monty ByteCodes file you want to interpret.

## Compilation

Compile the Monty interpreter using the following command:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
