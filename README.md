# alx-system_engineering-devops
# 0x03. Shell, init files, variables and expansions

This project is part of the **ALX Back End ProDev program**. It explores how to use shell initialization files, manage variables, understand expansions, and perform shell arithmetic.

---

## 📚 Learning Objectives

At the end of this project, you should be able to explain the following:

- What happens when you type `$ ls -l *.txt` in the shell
- Shell expansions and their types
- Shell variables – local vs global
- Shell arithmetic operations
- How to create, modify, and delete shell variables and aliases

---

## 📁 Project Structure

Each file corresponds to a task that demonstrates a specific concept. All scripts are executable and written for the Bourne shell (`#!/bin/bash`).

---

## ✅ Tasks

| Task # | Filename | Description |
|--------|----------|-------------|
| 0 | `0-alias` | Creates an alias named `ls` with the value `rm *` |
| 1 | `1-hello_you` | Prints `hello` followed by the current Linux user |
| 2 | `2-path` | Adds `/action` to the `PATH` environment variable |
| 3 | `3-paths` | Counts the number of directories in the `PATH` |
| 4 | `4-global_variables` | Lists all environment variables |
| 5 | `5-local_variables` | Lists all shell variables and functions |
| 6 | `6-create_local_variable` | Creates a local variable `BEST="School"` |
| 7 | `7-create_global_variable` | Creates a global variable `BEST="School"` |
| 8 | `8-true_knowledge` | Prints the result of adding 128 to the value of `TRUEKNOWLEDGE` |
| 9 | `9-divide_and_rule` | Prints the result of `POWER / DIVIDE` |
| 10 | `10-love_exponent_breath` | Displays the result of `BREATH` raised to the power of `LOVE` |
| 11 | `11-binary_to_decimal` | Converts a binary number stored in `BINARY` to decimal |
| 12 | `12-combinations` | Prints all combinations of two letters except `oo` |
| 13 | `13-print_float` | Prints a float value stored in `NUM` with two decimal places |
| 14 | `100-decimal_to_hexadecimal` | Converts a decimal stored in `DECIMAL` to hexadecimal |
| 15 | `101-rot13` | Encodes input using the ROT13 cipher |
| 16 | `102-odd` | Prints every other line of input, starting with the first |
| 17 | `103-water_and_stir` | Adds two encoded numbers and prints the result in base `bestchol` |

---

## 🧪 How to Run

Give executable permission and run the script:

```bash
chmod +x <filename>
./<filename>

