this is for the first read me compare the two 
# 📁 1_basic-linux-commands

## 🧭 Who is this for?
- Beginners with no IT experience
- Anyone curious about how Linux systems work
- AWS learners using Linux-based virtual machines

## 💡 What will you learn?
- Navigate file systems like folders in Windows/Mac
- Create, move, and delete files and directories
- View hidden files and understand Linux directory structure

## ⏱️ When should you learn this?
- Before working with cloud virtual machines (EC2)
- When preparing for AWS Cloud Practitioner or Associate exams

## 🌍 Where is this used?
- Linux terminals (Ubuntu, Amazon Linux, etc.)
- AWS EC2, CloudShell, coding bootcamps, and DevOps tools

## ❓ Why learn it?
Linux is the foundation of cloud computing. Mastering basic navigation and file handling makes all other skills easier to learn.

## 🔧 How does it work?
These commands mirror common file actions like navigating folders, viewing documents, and organizing content.

---

## 🔄 Core Commands
| Command | Description |
|---------|-------------|
| pwd   | Print working directory (shows your current location) |
| ls    | List files and folders in the current directory |
| cd    | Change directory (navigate) |
| mkdir | Make a new directory |
| touch | Create a blank file |
| rm    | Remove a file |
| rmdir | Remove an empty directory |
| ls -a | Show hidden files (those starting with .) |
| cd .. | Move up one directory |

---

## 📈 Diagram: Linux File System as a Tree
/
├── home
│   └── user
│       ├── documents
│       └── pictures
├── bin → essential programs
├── etc → configuration files
└── var → logs, cache


---

## 📝 Exercise: Hands-On Navigation
Open your terminal and try this:
bash
mkdir practice
cd practice
touch hello.txt
ls
pwd
cd ..
rm -r practice

🧠 What happened? You created a folder, navigated into it, added a file, and cleaned up.

---

## ❓ Quiz
**Q1:** What command lets you check where you are in the system?
- A) cd
- B) mkdir
- C) pwd

**Q2:** What does cd .. do?
- A) Moves into a folder named ..
- B) Goes up one level
- C) Deletes your current directory

**Q3:** What command creates a new empty file?
- A) mkdir  
- B) touch  
- C) ls

**Q4:** Which command shows hidden files in a directory?
- A) ls -l  
- B) ls -a  
- C) cd -a

✅ *Answers:* 1:C, 2:B, 3:B, 4:B

---

## ✅ Checklist
- [x] I can list files using ls
- [x] I understand pwd and cd
- [x] I can create and delete files and folders
- [x] I know how to view hidden files

---

🎯 You now have a solid foundation to navigate Linux like a pro. Practice using cd, ls, and mkdir regularly to get comfortable.
