# Task A - Extracting system calls from an executable
## Level 1

```
strace mkdir new_directory 2>&1 | tee mkdir_strace_output.txt
```
