# Journey into Obfuscation

## Ideas
 - Dynamically calculate system call numbers.
 - Self altering program; change which system calls are being made.
 - Many-threaded program. Master execution thread, rotates between other threads to get instructions for different functions. Hard to debug.
 - Use table of function pointers for calls, which table entry is calculated dynamically
 - 

 - Program can verify if injection has been made or if debugger makes changes by hash chaining previous data somehow???
