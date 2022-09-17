# Kiyoshika
My name is Zach, Kiyoshika is random alias I used in a game called RuneScape.

I'm a self-taught programmer but also pretty passionate about statistics.

I heavily prefer statically typed languages, more specifically C and C++. I love memory management and pointers even though it can be frustrating at times.

Despite my profile picture, I don't really watch much anime these days. But I may watch it once every few months.

# Quick Summary
Clearly I am a fan of C

![](https://raw.githubusercontent.com/kiyoshika/github-stats/master/generated/languages.svg#gh-dark-mode-only)
![](https://raw.githubusercontent.com/kiyoshika/github-stats/master/generated/languages.svg#gh-light-mode-only)

![](https://raw.githubusercontent.com/kiyoshika/github-stats/master/generated/overview.svg#gh-dark-mode-only)
![](https://raw.githubusercontent.com/kiyoshika/github-stats/master/generated/overview.svg#gh-light-mode-only)

# Projects
## General (Non-Embedded)
### Libraries
* [Generalized Modelling Framework (libgmf)](https://github.com/Kiyoshika/generalized-modelling-framework) - A very flexible optimization framework for building different types of predictive models with modularity in mind - like legos, but for predictive modelling.
* [hashmap](https://github.com/Kiyoshika/hashmap) - A generic hashmap that supports user-defined keys and values and dynamically grows in size.
* [lookup](https://github.com/Kiyoshika/lookup) - A generic and dynamically-sized lookup table data structure to support inserting chunks of data and performing many queries against it
* [Zumpy](https://github.com/Kiyoshika/Zumpy) - A numpy-inspired array module for Python written in C. I started this project to understand how to use shared libraries in other languages, specifically Python.
* [CMatrix](https://github.com/Kiyoshika/CMatrix) - A simple C matrix library for the learning experience.

### Algorithms
* [kdtree](https://github.com/Kiyoshika/kdtree) - A simple kdtree implementation in C for finding nearest neighbors. This is used in the KNN implementation in one of my libraries, [Generalized Modelling Framework (libgmf)](https://github.com/Kiyoshika/generalized-modelling-framework)
* [Generic Quicksort](https://github.com/Kiyoshika/Generic-Quicksort) - A templated generic quicksort algorithm in C++ to support native and user-defined data types.
* [Simple Expression Parser](https://github.com/Kiyoshika/Simple-Expression-Parser) - A simple mathematical expression parser that takes a character buffer representing a mathematical expression and returns the evaluated value as a float. This will be used in an upcoming embedded calculator project.
* [Quick Select](https://github.com/Kiyoshika/QuickSelect) - A simple implementation of the QuickSelect algorithm in C to find the k-th largest element in an unsorted array.

### Software
* [Vertisec](https://github.com/Kiyoshika/Vertisec) - A Vertica SQL parser to improve the bad error messages Vertica gives by default.
* [Source Tracker](https://github.com/Kiyoshika/Source-Tracker) - A heavily simplified "git" clone for local version control of files/code. I started this project to learn more about file management in C++ (using C++17's filesystem API).

## Embedded
### Libraries
* [HD44780 LCD Library](https://github.com/Kiyoshika/HD44780-STM32) - A lightweight library for the HD44780 16x2 character LCD for STM32 MCUs. This code in particular was written for STM32F411xx but with some code tweaks can support (in theory) any STM32 board.
* [Matrix Keypad Library](https://github.com/Kiyoshika/MatrixKeypad-STM32) - A simple library for dealing with matrix keypads. This code in particular was written for STM32F411xx but with some code tweaks can support (in theory) any STM32 board.
### Samples
* [UART Server Client](https://github.com/Kiyoshika/UART-Server-Client) - A sample project to show how to make two different MCUs communicate with each other over UART. This was written "bare metal" with no libraries (besides device headers).
### Software
* [Physical Clipboard Manager](https://github.com/Kiyoshika/Physical-Clipboard-Manager) - My second embedded project, a physical board with 8 buttons: 4 copy, 4 paste. When you press a copy button, it will fetch the current clipboard content and store it in FLASH memory on the MCU. When you press a paste button, it will retrieve the data from memory and paste it wherever your cursor currently is. This gives you 4 unique clipboards instead of the one default with Ctrl+C & Ctrl+V.
* [Clone Hero Controller](https://github.com/Kiyoshika/CloneHeroController) - My first embedded project, a minature game controller for playing Clone Hero assembled (messily) onto a breadboard with a STM32F411xx microcontroller.
