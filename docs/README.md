---
title: EECS 281 Search Demo
---

# EECS 281 Search Demo

## Download the Code

Download the source code from [https://eecs281staff.github.io/search-demo/search.cpp](https://eecs281staff.github.io/search-demo/search.cpp).

## Compiling the Code

On CAEN it is important to use a compiler that supports using C++11 or higher. As of Fall 2023, the default version (g++ 8.3.0) available upon logging into CAEN will do this.

``` console
$ mkdir search-demo && cd search-demo
$ g++ -std=c++17 -O3 search.cpp -o search
```

## Running the Demo

The compiled program takes two arguments: a single character to describe the type of search used, and a number of searches to perform. The search type is either linear (`'l'`) or binary (`'b'`). For the number of searches, try a broad range of values from thousands to millions to analyze the time complexity during execution.

``` console
$ ./search l 100000
$ ./search b 20000000
```
