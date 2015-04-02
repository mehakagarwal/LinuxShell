# Linux-shell-in-c-

A basic linux shell implementation in c++

Using POSIX library , implemented a basic shell in c++, which executes the standard linux commands.The key highlight is the execution of multiple pipes , and input and output redirection.

Direction to run the code:

COMPILE:  g++ -o shell myshell.cpp
Execute:  ./shell

Features covered:

1. History command
2. Multiple pipes
3. input output redirection
4. input output redirection along with single pipe.
5. Multiple pipes with redirection to output.
6. !(bang) operator [ !+, !-,!!]
7. basic environment variables ($PWD,$HOME etc...)
8. Basic linux commands (ls,clear,pwd,wc etc...)
9. change directory (cd) command
10. exit command
