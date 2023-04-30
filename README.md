# exed
Dump hex bytes of code section in EXE & DLL

### Intro

Your alternative reverse-engineering tool to hexdump code section of portable executable.

This `exed` is a variant of `exedump`, which omit file offset and ASCII characters.

### Screenshot

![cmd](https://pictr.com/images/2023/04/30/E4z2tX.png)

### Usage

Examples:

`exed file.exe | more` - Scroll line by line or page by page on screen

`exed file.exe > file.txt` - Redirect output to a text file

The content of output text file is ideal for copy and paste to an online disassembler.

### Build

Please compile with flat assembler, preferably with its `fasmw.exe` (IDE) so that you don't need to specify the path of `INCLUDE` file.
