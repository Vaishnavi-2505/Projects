# 🗂️ Marvellous CVFS (Customised Virtual File System)

### 📘 Description
A simple in-memory **Virtual File System** built in C/C++.  
It simulates UNIX-like file handling — supporting create, read, write, delete, and list operations.

---

### 👩‍💻 Author
**Vaishnavi D. Shingare**  
📅 *26 Jan 2025*

---

### ⚙️ Features
- Create and delete files  
- Read & write data  
- List and view file info  
- In-memory simulation (no disk)  
- Command-based shell interface  

---

### 💻 Commands
| Command | Description |
|----------|-------------|
| `creat <name> <perm>` | Create file (1=R, 2=W, 3=R+W) |
| `write <fd>` | Write data to file |
| `read <fd> <size>` | Read data from file |
| `ls` | List all files |
| `stat <name>` | Show file info |
| `unlink <name>` | Delete file |
| `help` / `man <cmd>` | Show help or manual |
| `clear` | Clear screen |
| `exit` | Exit CVFS |

---
📦 Limits

Max files: 5

Max open files: 20

Max file size: 100 bytes

### 🚀 Run

```bash
g++ CVFS.cpp -o CVFS
./CVFS


---

✅ This version includes all **essential info**: what it is, what it does, commands, how to run, limits, and author — perfect for a report or GitHub README.
