### Clue 3: Humans vs. Machines ###

#### Binary vs. Text ####

There are two basic types of files: binary and text. Text can be read by both
humans and the computer, and is sometimes referred to as "human-readable". For
example, the file you are reading right now is text.

Binary is a number system that uses only 0 and 1 as digits. For example, 42 is
represented as 101010 in binary. Each digit is called a "bit". Eight bits is
called a "byte". There are 2^8 = 256 possible bytes. Computers use a shorthand
for each byte called "hexadecimal" or more briefly "hex". In hex there are
sixteen digits, the usual 0-9 and also A-F. A is equal to 10, B to 11, *etc*.
Sometimes we write a `0x` in front of a hex number to indicate we are using
hex: 42 is `0x2A`.

If you ever look at a file and see a bunch of "garbage", you are probably
looking at a binary file. The content isn't intended for you: it's for the
computer. Binary files are sometimes referred to as "machine-readable".

#### `/bin` ####

One place you can always find binaries on a Linux system is in `/bin`.