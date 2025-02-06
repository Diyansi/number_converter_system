# Number System Converter

This is a simple C program that allows the conversion between different number systems such as Binary, Decimal, Octal, and Hexadecimal.

## Features

- **Binary Conversion**: Convert between Binary, Decimal, Octal, and Hexadecimal.
- **Decimal Conversion**: Convert between Decimal, Binary, Octal, and Hexadecimal.
- **Octal Conversion**: Convert between Octal, Binary, Decimal, and Hexadecimal.
- **Hexadecimal Conversion**: Convert between Hexadecimal, Binary, Octal, and Decimal.

## Functionalities

- Users can select the type of conversion (Binary, Decimal, Octal, Hexadecimal).
- The program checks for valid input and gives an error message if invalid characters are entered.
- It allows users to try again after a conversion or exit the program.

## How to Use

1. When the program starts, a menu is displayed where you can choose which type of conversion you want to perform:
    - Binary Conversion
    - Decimal Conversion
    - Octal Conversion
    - Hexadecimal Conversion
    - Exit the Program

2. After selecting a conversion type, enter the number in the respective format.
3. The program will display the conversion results in the selected number systems.
4. You can choose to perform another conversion or exit.

## Example

### Conversion from Binary to Decimal:

### Conversion from Decimal to Binary:

## Error Handling

- If an invalid number is entered (e.g., a non-binary digit for binary conversion), the program will display an error message.
- For hexadecimal input, only characters `0-9` and `A-F` (case-insensitive) are allowed.
- For octal input, only digits `0-7` are allowed.

## Installation

To run the program:

1. Copy the code into a `.c` file (e.g., `number_system_converter.c`).
2. Compile the program using a C compiler.
    ```bash
    gcc number_system_converter.c -o converter
    ```
3. Run the program:
    ```bash
    ./converter
    ```

## License

This program is free to use for educational purposes. You can modify and redistribute it as you like.

---

### Author: [Diyansi Chaudhary]
