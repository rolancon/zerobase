# Zerobase (0z)

This system to generalize representation of integer numbers in any base up to base-32 works as follows:
- The number in any base starts with the zero digit (`0`), followed by the digit (`0-9`) or letter (`a-z`) that specifies in which base the number is represented, followed by the **w**hichever-base indicator (`w`), followed by by the number itself. The letters are case-insensitive (lowercase is preferred over uppercase though).
- The digits represent the highest number that can be specified in that base. Digits give from one (`0`) to ten (`9`) possibilities, so `00w` typifies base-1 (numbers are represented by the number of zero digits), and and `09w` typifies base-10 (the same as normal decimal numbers without prefix).
- The letters represent bases above 10 in their alphabetical ordering. Letters give from 11 (`a`) to 36 (`z`) possibilities. So `0aw` typifies base-11. However, the 4 highest letters (`w-z`) have a special meaning (`w` is shown already), therefore there at most 32 bases. Therefore `0vw` represents the highest possible base type (base-32).
- Base-x (`0x`) represents he**x**idecimal numbers, and is therefore the same as base-16 (`0fw`). The same as `0h`.
- Base-y (`0y`) represents binar**y** numbers, and is therefore the same as base-2 (`01w`). The same as `0b`.
- Base-z (`0z`) represents the **z**erobase, the absence of any (possible) number, and is a shorthand for the name of this system (Zerobase).
