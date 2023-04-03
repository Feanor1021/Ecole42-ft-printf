# Ecole42-ft-printf

The Ecole42-ft-printf project is a recreation of the standard C library's `printf` function. The purpose of this project is to learn how to parse input arguments, format strings, and output formatted data in C programming.

## Usage

To use the ft_printf function, simply include the `ft_printf.h` header file in your program, and call the `ft_printf` function with the format string and any additional arguments. The function returns the number of characters printed.

```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello, %s!\n", "world");
    return (0);
}
```

## Supported Format Specifiers

The ft_printf function supports the following format specifiers:

| Specifier | Description |
| --- | --- |
| `%c` | Character |
| `%s` | String |
| `%p` | Pointer |
| `%d` | Signed decimal integer |
| `%i` | Same as `%d` |
| `%u` | Unsigned decimal integer |
| `%x` | Unsigned hexadecimal integer (lowercase) |
| `%X` | Unsigned hexadecimal integer (uppercase) |
| `%%` | Prints a literal `%` character |

## Example

Here is an example of how to use the ft_printf function to output formatted text:
```c
#include "ft_printf.h"

int main(void)
{
    int x = 42;
    ft_printf("The answer to the universe is %d.\n", x);
    return (0);
}
```
This will output:
```c
The answer to the universe is 42.
```
