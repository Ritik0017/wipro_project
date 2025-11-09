# 🐚 Custom Linux Shell 
### Operating Systems & Linux System Programming Project

---

## 📘 1. Introduction

The **Custom Linux Shell (Mini-Shell)** is a terminal-based C++ program that mimics the functionality of a Linux command-line shell.  
It supports **command execution**, **I/O redirection**, **piping**, and **background job management**, offering a deep understanding of **process creation**, **inter-process communication**, and **system calls** in Linux.

This project demonstrates practical use of **fork(), execvp(), waitpid(), pipe(), dup2()**, and other **POSIX APIs** in a real-world scenario.

---

## 🧩 2. Project Explanation

The Mini-Shell interprets and executes user commands, providing features similar to a basic Unix shell.

### 🧱 Features Implemented:
- Execute Linux commands (e.g., `ls`, `cat`, `pwd`, etc.)
- Foreground and Background process execution (`&`)
- I/O Redirection (`>`, `<`)
- Piping (`|`)
- Built-in commands:
  - `cd` → Change directory  
  - `jobs` → List running background jobs  
  - `fg <jobid>` → Bring a background job to foreground  
  - `kill <jobid>` → Terminate a background job  
  - `exit` → Exit the shell

### 🧠 Key Learning Outcomes:
- Process management using `fork()` and `execvp()`
- Implementing I/O redirection using `dup2()` and `open()`
- Building a pipeline between processes using `pipe()`
- Job control and process synchronization using `waitpid()`
- Command parsing and tokenization using C++ strings and STL

---

## ⚙ 3. Requirements

### 🧭 Software:
- **Operating System:** Linux (Ubuntu/Debian recommended)
- **Compiler:** `g++` version 9.0 or higher
- **Libraries:**  
  - Standard C++ STL  
  - POSIX system libraries (`unistd.h`, `sys/wait.h`, `fcntl.h`)

### 🗃 Hardware:
- Minimum **4 GB RAM**
- Any **dual-core CPU or higher**

### 📦 Optional (for development & GitHub):
- Git
- Visual Studio Code / CLion / any C++ IDE

## 🏁 4. Conclusion

The Custom Linux Shell Implementation project successfully demonstrates the internal working of a basic command-line shell environment using C++ and Linux system calls.

Through this project, key operating system concepts such as process creation, process synchronization, inter-process communication, and I/O redirection were practically implemented. The shell can execute external commands, manage foreground and background processes, handle piping between commands, and perform input/output redirection using file descriptors.

---

## 👨‍💻 5. Author

*Ritik Rout*  
Final Year – Computer Science and Engineering 


---

## 📜 6. License

This project is licensed under the *MIT License*.  
You’re free to use and modify this project with proper credit.

```

MIT License  
Copyright (c) 2025 Ritik Rout
```

