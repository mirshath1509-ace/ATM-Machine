# Simple C Programs

This repository contains two beginner-friendly C programs.

## Programs

### 1. Simple Calculator (`simple_calculator_switch.c`)
A calculator that takes two numbers and an operator, then prints the result.
- Supported operators: `+`, `-`, `*`, `/`
- Uses a `switch` statement

### 2. Simple ATM Machine (`simple_atm.c`)
An ATM program with a menu of options.
- Check balance
- Deposit money
- Withdraw money
- Exit
- Starting balance is 5000

## Requirements
- GCC compiler (or any C compiler)

## How to Compile and Run

Calculator:
```bash
gcc simple_calculator_switch.c -o calculator
./calculator
```

ATM:
```bash
gcc simple_atm.c -o atm
./atm
```

## Sample Output

Calculator:
```
Enter first number: 10
Enter operator (+, -, *, /): *
Enter second number: 5
Result = 50.00
```

ATM:
```
===== ATM MACHINE =====
1. Check Balance
2. Deposit
3. Withdraw
4. Exit
Enter your choice: 1
Your balance is: 5000.00
```

## Concepts Used
- Variables and data types
- `scanf` and `printf`
- `switch` statement
- `if` / `else`

## Author
Your Name
