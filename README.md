# C++ Print Statements
The following project details how print statements work in C++. This includes but is not limited to: printing constant statements, printing variable statements, the usage of '\t' and '\n' and using keywords such as 'cout' and 'endl'.

## Hello World in C++
The following program is a 'Hello World' program in C++. In Computer Science, 'Hello World' programs are considered the most basic program that a programmer can create. The purpose of a 'Hello World' program is to give the programmer some familarity in the basic syntax of the programming language they are working with. There are several things of interest to note here. Take a look at the general structure of the program. What do you notice about it? 

```c++
#include <iostream>

using namespace std;

int main(int argc, char* argv[])
{
    cout << "Hello World!";
    return 0;
}
```

The output of this program is: 

```
Hello World!
```

How exactly does this program work though? Let's start by breaking it down piece by piece.

## Required Import Statements in C++

One thing that may stand out to you in the 'Hello World' program is the following statement:

```c++
#include <iostream>
```

This is what we call an 
