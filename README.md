# Zerobase (0z)

This system to generalize representation of integer numbers in any base up to base-32 works as follows:
- The number in any base starts with the digit (`0-9`) or letter (`a-z`) that specifies in which base the number is represented, followed by the *w*hichever-base indicator (`w`), followed by by the number itself. The letters are case-insensitive (lowercase is preferred over uppercase though).
- The digits represent the highest number that can be specified in that base. Digits give from one (`0`) to ten (`9`) possibilities, so `0w` typifies base-1 and and `9w` typifies base-10 (the same as decimal numbers).
- The letters represent bases above 10 in their alphabetical ordering. Letters give from 11 (`a`) to 36 (`z`) possibilities. So `aw` typifies base-11. However, the 4 highest letters (`w-z`) have a special meaning in a slightly different notation, therefore there at most 32 bases. Therefore `vw` represents the highest possible base type (base-32).
- Base-x (`0x`) represents he*x*idecimal numbers, and is therefore the same as base-16 (`fw`).
- Base-y (`0y`) represents binar*y* numbers, and is therefore the same as base-2 (`1w`).
- Base-z (`0z`) represents the absence of any (possible) number, and is a shorthand for the name of this system (*z*erobase).
