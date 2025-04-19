# Custom Unix Shell

## Overview
This project is a fully functional Unix-like shell implemented from scratch. It provides command parsing, job execution, and support for both built-in and external commands, along with basic I/O redirection.

The shell mimics key functionalities of standard Unix shells, offering users the ability to execute commands interactively and manage processes.

## Features

### ✅ Internal Commands
- Commands that are handled entirely within the shell without spawning new processes.
- Examples: `cd`, `chprompt`, `showpid`, `jobs` , `fg` , `quit` and `kill`.

### ✅ External Commands
- Commands that are executed in a separate process using `fork()` and `execv()`.
- Examples: `ls`, `cat`, `grep`, etc.

### ✅ Special Commands: Output Redirection
- Supports output (`>`, `>>`) redirection.

### 🔄 Job Execution
- Executes foreground jobs and waits for them to complete.
- Added background process support by allowing the shell to continue without waiting for the child process to complete.




