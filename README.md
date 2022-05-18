# Kiyoshika
My name is Zach, Kiyoshika is random alias I used in a game called RuneScape.

I'm a self-taught programmer but also pretty passionate about statistics.

I heavily prefer statically typed languages, more specifically C and C++. I love memory management and pointers even though it can be frustrating at times.

Despite my profile picture, I don't really watch much anime these days. But I may watch it once every few months.

# Toolkit
* **C99** - Currently my primary programming language
* **C++17** - Secondary programming language
* **Python** - Usually only use this when I have to, although I am now working on some C --> Python bindings for practice
* **R** - Only use this for statistical projects; I have a few repos on here that show some things I've built with R.

# Projects
## General (Non-Embedded)
### Libraries
* [Generalized Model Framework (libgmf)](https://github.com/Kiyoshika/Generalized-Model-Framework) - A very flexible optimization framework for building different types of predictive models with modularity in mind - like legos, but for predictive modelling.
* [Zumpy](https://github.com/Kiyoshika/Zumpy) - A numpy-inspired array module for Python written in C. I started this project to understand how to use shared libraries in other languages, specifically Python.
* [C-CSV-Parser](https://github.com/Kiyoshika/C-CSV-Parser) - A simple CSV parser which supports reading full CSV files or only specific columns and casting data to int/float.
* [C-Hash-Map](https://github.com/Kiyoshika/C-Hash-Map) - A custom hashmap implementation for C which relies on another of my projects, [C-Linked-List](https://github.com/Kiyoshika/C-Linked-List) which is a linked list implementation for C.

### Algorithms
* [Generic Quicksort](https://github.com/Kiyoshika/Generic-Quicksort) - A templated generic quicksort algorithm in C++ to support native and user-defined data types.
* [Simple Expression Parser](https://github.com/Kiyoshika/Simple-Expression-Parser) - A simple mathematical expression parser that takes a character buffer representing a mathematical expression and returns the evaluated value as a float. This will be used in an upcoming embedded calculator project.

### Software
* [Source Tracker](https://github.com/Kiyoshika/Source-Tracker) - A heavily simplified "git" clone for local version control of files/code. I started this project to learn more about file management in C++ (using C++17's filesystem API).

## Embedded
### Libraries
* [HD44780 LCD Library](https://github.com/Kiyoshika/HD44780-STM32) - A lightweight library for the HD44780 16x2 character LCD for STM32 MCUs. This code in particular was written for STM32F411xx but with some code tweaks can support (in theory) any STM32 board.
### Samples
* [UART Server Client](https://github.com/Kiyoshika/UART-Server-Client) - A sample project to show how to make two different MCUs communicate with each other over UART. This was written "bare metal" with no libraries (besides device headers).
### Software
* [Physical Clipboard Manager](https://github.com/Kiyoshika/Physical-Clipboard-Manager) - My second embedded project, a physical board with 8 buttons: 4 copy, 4 paste. When you press a copy button, it will fetch the current clipboard content and store it in FLASH memory on the MCU. When you press a paste button, it will retrieve the data from memory and paste it wherever your cursor currently is. This gives you 4 unique clipboards instead of the one default with Ctrl+C & Ctrl+V.
* [Clone Hero Controller](https://github.com/Kiyoshika/CloneHeroController) - My first embedded project, a minature game controller for playing Clone Hero assembled (messily) onto a breadboard with a STM32F411xx microcontroller.
