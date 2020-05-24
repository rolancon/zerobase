# Zerobase (0z)

This system to generalize representation of integer numbers in any base up to base-32 works as follows:
- The number in any base starts with the digit (`0-9`) or letter (`a-z`) that specifies in which base the number is represented, followed by the *w*hichever-base indicator (`w`), followed by by the number itself.
- The digits represent the highest number that can be specified in that base. Digits give from one (`0`) to ten (`9`) possibilities, so 00 typifies base-1 and and 09 typifies base-10.
- The letters represent bases above 10 in their alphabetical ordering. Letters give from 11 (`a`) to 36 (`z`) possibilities. So `0a` typifies base-11. However, the 4 highest letters (`w-z`) have a special meaning, therefore there at most 32 bases. Therefore `0v` represents the highest possible base type (base-32).
- Base-x (`0x`) represents he*x*idecimal numbers, and is therefore the same as base-16 (`0f`).
- Base-y (`0y`) represents binar*y* numbers, and is therefore the same as base-2 (`01`).
- Base-z (`0z`) represents the absence of any (possible) number, and is a shorthand for the name of this system (*z*erobase).
