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

## Import Statements in C++

One thing that may stand out to you in the 'Hello World' program is the following statement:

```c++
#include <iostream>
```

In Computer Science we call this an **import statement**. In Computer Science, there are endless possibilities when it comes to the things we can do; because of this, it is often nessecary to include import statements in our code to be able to access the libraries we need. In a C++ program, you will always need to import the **iostream**. If you choose to study Computer Science at the advanced level, you will learn what this library does, however, for our purposes just think of it as a magic required statement. In addition it is common practice to also have the following statement in a C++ program:

```c++
using namespace std;
```
Although the statement above is not technically considered an import statement, it is easier to think of it as one. Calling the statement above tells the computer that the syntax we are using is in line with the syntax of the standard library. If we were to not include this statement, then we could run into some issues accessing various functions and methods in our program.

## The main() function in C++

In Computer Science, the main() function is used as a startng point for the computer. In order to run any code in a computer science program, it has to be linked to the main() function in some way. The basic structure of a main() function in C++ is:

```c++
int main(int argc, char* argv[])
{
    cout << "Hello World!";
    return 0;
}
```
