## 🛠️LIBFT:
*This activity has been created as part of the 42 curriculum by kmaghair.*
**********************************************************************************************
## 📃ABOUT

 The goal of this project is to build a custom C function library. This library serves as a foundational toolkit, recreating standard C library functions alongside custom utility functions, which will be utilized and expanded upon in future C programming assignments throughout the core curriculum.
**********************************************************************************************
## ⚙️  WHAT THE FUNCTIONS DO

The functions in this library are custom-built recreations of standard C library (`libc`) functions, alongside several extra utility tools. Because standard functions are often restricted in future projects, this library serves as a foundational toolkit to handle common programming tasks from scratch. 

In general, the functions accomplish tasks across four main categories:

* **Memory Management:** Functions that allow you to allocate dynamic memory safely, copy data from one memory block to another, search for specific bytes, and erase or overwrite memory areas.
* **String Manipulation:** Tools to calculate string lengths, duplicate, copy, join, split, trim, and search through strings. This also includes functions that let you apply a specific action to every character in a string.
* **Character Classification & Conversion:** Simple checks to determine if a character is a letter, a number, or printable, as well as tools to swap characters between lowercase and uppercase.
* **Output & File Descriptors:** Functions designed to print characters, strings, and numbers directly to the terminal or to specific files using file descriptors.
**********************************************************************************************
## 🚀 INSTRUCTIONS

This library is written in C and adheres strictly to Norminette formatting rules.

**To compile the library:**
1. Navigate to the root of the repository.
2. Run `make` to compile the source code and generate the static library file (`libft.a`).

**Available Make Commands:**
* `make` - Compiles the `.c` files and creates `libft.a`.
* `make clean` - Removes the compiled object (`.o`) files.
* `make fclean` - Removes the object files and the `libft.a` file.
* `make re` - Fully recompiles the library from scratch.
**********************************************************************************************
## 📚 RESOURCES

* Official Linux `man` pages for standard C library function behaviors.
* **AI Usage:** AI was utilized to clarify strict compilation flag behaviors, assist with debugging dynamic memory allocation logic, and help review Norminette formatting requirements during the development of custom string functions.
**********************************************************************************************
