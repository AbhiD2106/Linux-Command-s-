# Linux/CMD Commands Practice

A log of basic file and directory commands practiced in a Windows terminal (Git Bash / Unix-style commands).

## 📁 Navigation & Directory Management

```bash
pwd                     # Print working directory
ls                       # List files and directories
ls -a                    # List all files, including hidden ones
ls -l                    # List in long format
ls -lh                   # Long format with human-readable sizes
ls -lha                  # Long format, all files, human-readable sizes
cd                       # Go to root/home directory
cd TDPCL                 # Move into TDPCL directory
cd ..                    # Move up one directory
mkdir cmd_commands       # Create a new directory
cd cmd_commands          # Move into the new directory
```

## 📄 File & Folder Creation/Deletion

```bash
mkdir demo.txt           # Create a directory (note: .txt here is just a folder name)
rmdir demo.txt           # Remove an empty directory
mkdir demo               # Create "demo" directory
```

## 📦 Copy & Move

```bash
cp mytxt.txt demo        # Copy a file into the demo folder
mv mytxt.txt demo        # Move a file into the demo folder
mv filee.txt myfile.txt  # Rename a file
mv filee.txt E:\cmd_commands   # Move a file to another path
```

## 🗑️ Removing Files/Folders

```bash
rm mytxt.txt             # Remove a file
rm -r cmds.txt           # Remove a directory and its contents recursively
```

## 📖 Viewing & Creating File Content

```bash
cat myfile.txt           # Display file content
cat > abhi.txt           # Create a new file and type content (Ctrl+D / Ctrl+Z to save)
cat abhi.txt             # Display file content
cat *.txt                # Display content of all .txt files
cat copy.txt > paste.txt # Overwrite paste.txt with copy.txt's content
cat copy.txt >> paste.txt # Append copy.txt's content to paste.txt
cat copy.txt paste.txt >> murge.txt  # Merge multiple files into one
```

## 📊 Disk Usage

```bash
du                       # Show disk usage of files/folders
du -h                    # Show disk usage in human-readable format
```

## 🔍 Searching with grep

```bash
grep abhi abhi.txt       # Search for "abhi" in a specific file
grep copy copy.txt       # Search for "copy" in a specific file
grep abhi *.txt          # Search for "abhi" across all .txt files
```

## 🧹 Other Useful Commands

```bash
clear                    # Clear the terminal screen
exit                     # Exit the terminal session
```

---

### 📝 Notes
- `ls`, `cd`, `mkdir`, `cp`, `mv`, `rm`, `cat`, `grep`, `du` are core commands for navigating and managing files — essential for Data Engineering work involving servers, Docker, Spark clusters, and cloud VMs (which mostly run Linux).
- `>` overwrites a file with output, while `>>` appends to it.
- Always double-check before using `rm -r`, as it deletes directories and their contents permanently.
