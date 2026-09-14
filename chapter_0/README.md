# 📄 Chapter 0 — Introduction & First Program

## 🧭 What this lesson covers
What programming is, what C is, why it's used, setting up VS Code + the MinGW GCC compiler, and writing/running the first C program.

## 📁 File
[`01_first.c`](./01_first.c)

## 🏗️ Structure
-  `#include <stdio.h>` — pulls in the standard I/O library for `printf()`
-  `int main() { ... }` — the entry point every C program starts executing from
-  `printf("Hello World!");` — prints the text to the screen (no `\n`, so no trailing newline)
-  `return 0;` — signals the program ended successfully

## 🔑 Key concepts introduced
-  C is a compiled language — source code is translated to machine code before it runs
-  Every C program's execution starts from `main()`
-  Statements are terminated with a semicolon (`;`)
-  `printf()` is a library function, not a language keyword
-  `return 0` at the end of `main()` indicates success

## 🚧 Not yet covered here
-  Variables, constants, and keywords (next: chapter_1)
-  Taking input with `scanf()`
-  Comments (`//` and `/* */`)
-  Compilation steps in detail (this file just runs the compiled output)

## ▶️ How to view
Compile with `gcc 01_first.c -o 01_first` and run the resulting executable from the terminal. A pre-built `01_first.exe` is also included in this folder.