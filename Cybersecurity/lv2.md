# Task A - Extracting system calls from an executable
 ## Level 2
 
 Compile the program
 ```
g++ print_info.cpp -o test.out
```
 
Extract system calls and save to test_syscalls.txt
```
strace -o test_syscalls.txt ./test.out
```
