# C & C++ Compiler-Code-Analyzer-Project

A mini compiler and code analyzer developed in **C++** that simulates the core front-end phases of a real compiler.  
This project analyzes simplified C/C++ code to detect errors, build a symbol table, and generate intermediate and three-address code.

---

##  Project Objectives

- Understand compiler design concepts practically  
- Implement lexical, syntax, and semantic analysis  
- Detect and recover from common programming errors  
- Generate intermediate and three-address code  
- Provide structured output for learning purposes  

---

##  Major Modules

- **Lexical Analyzer** – Converts source code into tokens  
- **Syntax Analyzer** – Checks basic grammar rules  
- **Semantic Analyzer** – Validates variable usage and declarations  
- **Symbol Table** – Stores variable names and data types  
- **Intermediate Code Generator** – Produces expression-level code  
- **TAC Generator** – Generates three-address instructions  
- **Error Handler** – Detects and auto-corrects common errors  

---

##  Types of Errors Handled

- Missing semicolon  
- Undeclared variable usage  
- Variable redeclaration  
- Division by zero  
- Invalid declarations  

---

##  Features

- Token generation (Lexical Analysis)  
- Symbol table creation  
- Intermediate code generation  
- Three-address code (TAC) generation  
- Automatic error recovery  
- Console-based output  
- Modular and structured C++ code  

---

##  Technologies Used

- **Language:** C++  
- **Libraries:** STL (`vector`, `map`, `set`, `stack`)  
- **Input:** User-entered Mini C code  
- **Output:** Console-based analysis and reports  

---

##  Sample Test Cases

- Program with missing semicolon  
- Program with undeclared variable  
- Program with redeclared variable  
- Division by zero case  
- Correct input program
  
  Sample input:
int x
y = 5;
int x;
z = x / 0;
a = b + 3
#

---

##  Limitations

- Supports only a subset of C/C++ syntax  
- No full grammar-based parsing (LL/LR not implemented)  
- No machine code generation  
- No optimization techniques  

---

##  Future Enhancements

- Add full grammar-based parsing  
- Implement Abstract Syntax Tree (AST)  
- Support loops, conditions, and functions  
- Add code optimization  
- Develop GUI version  

---

##  Conclusion

This project demonstrates the fundamental working of a compiler by implementing lexical analysis, syntax checking, semantic validation, and intermediate code generation.  
It serves as an educational tool for understanding compiler design concepts through practical implementation.
