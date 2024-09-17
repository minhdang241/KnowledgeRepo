 
# Compiler
- Clang vs GCC:
	- Clang: developed by Apple
	- GCC: developed by the GNU project.
		-  GNU project is a free software that  provides a UNIX-like operating system and other softwares including the GCC complier.
- Complier process: *.c file -> *.o file -> 
```
program.c      →    Preprocessing    →    program.i (expanded C code)
program.i      →    Compilation      →    program.s (assembly code)
program.s      →    Assembly         →    program.o (object code)
program.o + Libraries → Linking     →    program (executable)
```

# Input / Output
`getchar`/`putchar`:  read/write a sing character.
# Pointers
The behavior when comparing 2 pointers pointing to 2 difference objects are not  determined.
`size_t`: unsigned integer type

Valid Pointer Ops:
- Adding/Subtracting pointer with an integer
- Assigning pointer to another same-type pointer
- Assigning or comparing pointer to zero.
- Subtracting/Comparing 2 pointers pointing to members of the same array.
# UNIX System Interface
> Unix philosophy: "everything is a file."

- `file-descriptor`: a non-negative integer, which is used to represent the file, instead of the file name. All the information about an open file is maintained by the system; the user program refers to the file by only the `file-descriptor`.
- When the `shell` runs a program, 3 **standard file descriptor** are opened for every process: stdin (fd0), stdout(fd1), and stderr(fd2).


