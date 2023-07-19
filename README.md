# Educational Assembly Intel IA-32 Programs

Welcome to this educational repository containing programs written in Assembly language for Intel IA-32 architecture, using the NASM assembler. The primary purpose of this repository is to provide resources for learning Assembly language and understanding computer architecture concepts.

## Repository Description

The programs in this repository are designed to help learners explore various aspects of Assembly language and gain insights into low-level computer architecture. Each program is accompanied by explanatory comments to aid understanding and foster a better learning experience.

## Directory Structure

The repository has the following structure:

```
└── src
    ├── files
    │   └── create_write.asm
    ├── funcs
    │   ├── inherit.asm
    │   ├── local_vars.asm
    │   └── void.asm
    ├── hello
    │   └── hello.asm
    ├── io
    │   └── in_out.asm
    ├── modules
    │   ├── hello.asm
    │   └── print.asm
    └── strings
        ├── atoi.asm
        ├── itoa.asm
        └── removeNL.asm
```

## Program Descriptions

1. **files/create_write.asm**: This program demonstrates file creation and writing operations in Assembly language.

2. **funcs/inherit.asm**: This program illustrates function inheritance in Assembly language.

3. **funcs/local_vars.asm**: This program showcases the usage of local variables in functions using Assembly language.

4. **funcs/void.asm**: This program demonstrates the implementation of functions with void return type in Assembly language.

5. **hello/hello.asm**: A simple "Hello, World!" program written in Assembly language.

6. **io/in_out.asm**: This program demonstrates input and output operations in Assembly language.

7. **modules/hello.asm**: This program contains a reusable module for printing "Hello, World!".

8. **modules/print.asm**: This program is a reusable module for generic string printing.

9. **strings/atoi.asm**: An implementation of the atoi (ASCII to integer) function in Assembly language.

10. **strings/itoa.asm**: An implementation of the itoa (integer to ASCII) function in Assembly language.

11. **strings/removeNL.asm**: This program removes newline characters from a string in Assembly language.

## Usage

To assemble and run any of these programs, make sure you have NASM installed on your Linux i386 machine. Then, follow these steps:

1. Navigate to the specific program directory using the terminal.
2. Assemble the program using NASM:

   ```
   nasm -f elf32 -o program_name.o program_name.asm
   ```

   Replace `program_name` with the name of the program you want to assemble.

3. Link the object file to create an executable:

   ```
   ld -m elf_i386 -s -o program_name program_name.o
   ```

   Replace `program_name` with the name of the program you want to create.

4. Run the executable:

   ```
   ./program_name
   ```

   Replace `program_name` with the name of the program you want to run.

## Contributing

This repository is open to contributions from anyone interested in enhancing the learning experience of Assembly language and computer architecture. If you'd like to add new programs, improve existing ones, or suggest any educational resources, feel free to open a pull request. Let's learn and grow together!

## License

This repository is open-source and available under the [MIT License](LICENSE). Happy learning!
